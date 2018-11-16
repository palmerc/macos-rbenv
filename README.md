ansible-role-macos-rbenv
========================

An ansible role to install rbenv and gems based on the work of [Hiroaki Nakamura](http://hnakamur.github.io)

Role Variables
--------------

 * `rbenv_ruby_version` is used to specify the version of ruby to be installed
 * `rbenv_global_gems` gems to install install in the global version of ruby

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - palmerc.macos-rbenv

License
-------

MIT

Author Information
------------------

Cameron Lowell Palmer