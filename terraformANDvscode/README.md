# my awesome TF module
This solves all your infrastructure neews. (Just kidding, this, is just an example :) )

## Usage
Sample usage:
~~~
module "my_ec2_instande" {
  source = "github.com/OVolt/myTestEnvironment/"   # enter the github repo
  version = "1.0"

  ec2_instance_tye    = "t3.micro"
  ec2_instance_name   = "My instance"
  number_of_instances = 1
  ec2_ami_id          = <your AMI ID to use to launch the instance>
}
~~~