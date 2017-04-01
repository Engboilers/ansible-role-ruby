# Ansible Role: Ruby

[![Build Status](https://travis-ci.org/engboilers/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/engboilers/ansible-role-ruby)

Installs ruby and global ruby gems.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    ruby_versions: []

Ruby versions you would like to make sure are installed with rbenv.

    ruby_global_gems: []

Global Ruby gems you would like to make sure are installed.

## Dependencies

  - [engboilers.homebrew](https://galaxy.ansible.com/engboilers/homebrew/)

## Example Playbook

    - hosts: localhost
      roles:
        - { role: engboilers.ruby, ruby_execute: true }

## License

Apache 2.0
