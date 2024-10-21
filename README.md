# Ansible Role: SVN

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

Installs [Apache SVN](https://subversion.apache.org/) (Subversion) on any RHEL/CentOS or Debian/Ubuntu Linux system.

## Requirements

The `svnserve` service, which allows access to repositories via the `svn://` protocol runs on port 3690 by default, so please make sure that port is open on your firewall.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    svn_repository_home: /var/svn

The SVN repository directory that will be served by `svnserve` through Apache.

    svn_create_test_repo: true

Whether to create a example respository 'testrepo', which will be available at `http://[hostname]/svn/testrepo`.

## Dependencies

  - nholuong.apache

## Example Playbook

    - hosts: servers
      roles:
        - nholuong.svn

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
