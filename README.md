s3fs
====

Ansible role to install [s3fs](https://github.com/s3fs-fuse/s3fs-fuse), a FUSE-based file system backed by Amazon S3.

Role Variables
--------------

- *s3fs_version*: s3fs version to install, defaults to `1.77`.
- *s3fs_install_prefix*: Install prefix, defaults to `/usr`.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - s3fs

License
-------

Apache v2

Author Information
------------------

Pierre Buyle <buyle@pheromone.ca>
