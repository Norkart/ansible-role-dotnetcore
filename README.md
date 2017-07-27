Role Name
=========

Installs dotnetcore on Ubuntu

Requirements
------------

None

Role Variables
--------------

The role includes dotnet version variables. For now the dev branch is the one being used. If it is changed to prod or nothing, branch should be replaced accordingly. The default settings creates the following package name: dotnet-dev-1.0.4

dotnet:
  branch: "-dev" 
  version:
    major: 1
    minor: 0
    patch: 4



Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - kjartab.dotnetcore
        

License
-------

MIT

Author Information
------------------

Kjartan Bjørset - Norkart AS