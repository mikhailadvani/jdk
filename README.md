jdk
=========
[![Build Status](https://travis-ci.org/mikhailadvani/jdk.svg?branch=master)](https://travis-ci.org/mikhailadvani/jdk) [![Galaxy](https://img.shields.io/badge/ansible--galaxy-mikhailadvani.jdk-blue.svg)](https://galaxy.ansible.com/mikhailadvani/jdk)

Install JDK 8

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: mikhailadvani.jdk, java_download_url: http://download.oracle.com/otn-pub/java/jdk/8u121-b13/e9e7ea248e2c4826b92b3f075a80e441/jdk-8u121-linux-x64.rpm }

License
-------

Apache