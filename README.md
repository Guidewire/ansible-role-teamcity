# teamcity

Roles tested on centos 6 and 7. Should work on ubuntu 16.04, might work on older versions as well.

## Requirements

Java is required, [this role](/ansiblebit/oracle-java) is recommended.

## server

Server role is implemented mostly to check agent role, it installs latest teamcity server without any configuration or DB drivers.
Manual server configuration is required via web wizard.

## build agent

Agent role was inspired by [this role](/matisku/ansible-teamcity-agent).
