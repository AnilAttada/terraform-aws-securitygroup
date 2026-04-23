# AWS SECURITY GROUP
* You can create a security group using this module. 

## Inputs
* project(Required) - Users should specify the name of project.

* environment(Required) - Users should specify the name of environment.

* sg_name(Required) - Users should specify the name of security group.

* sg_description(Required) - Users should specify the description of securty gruop they are creating. 

* vpc_id(Required) - Users should specify the ID of vpc in which they are creating the security group.

## Outputs
* sg_id - Security Group ID of the security group created using this module.