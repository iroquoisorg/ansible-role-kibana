# kibana

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-kibana.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for kibana

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.kibana`

# Default settings

```
kibana_version: "4.5"
kibana_server_host: "localhost"
kibana_server_port: "5601"
kibana_user: kibana
kibana_password: kibana
kibana_logging_silent: false
kibana_logging_quiet: false
kibana_logging_verbose: true
kibana_key_id: 'D88E42B4'
logstash_localsyslog_port: 5000
logstash_syslog_port: 5044

```
