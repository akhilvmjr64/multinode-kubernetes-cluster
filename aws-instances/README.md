Role Name
=========

Launch instances with tags as master and slave. One master is launched always.

Requirements
------------

- awscli
    aws cli must be installed and configured before using the role
- boto
- boto3

Role Variables
--------------

- `region`:
    Region in AWS
- `subnet`
    Subnet in AWS
- `keypair_name`
    Name of the keypair the same key pair will be used to launch the instances
- `instance_type`
    Type of the instance
- `instance_ami`
    AMI of instance
- `slavesNumber`
    Number of slaves

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
