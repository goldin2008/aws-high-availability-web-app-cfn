# Udacity Cloud DevOps Engineer Nanodegree Program - Project 2: Deploy a high-availability web app using CloudFormation

## Solution

### Create the stacks

To create the stacks, run the following commands:

```
./create-stack.sh <stack-name-network> network.yml network-parameters.json
./create-stack.sh <stack-name-server> server.yml server-parameters.json
./create-stack.sh <stack-name-bastion-host> bastion-host.yml bastion-host-parameters.json
```

### Update the stacks

To update the stacks, run the following commands:

```
./update-stack.sh <stack-name-network> network.yml network-parameters.json
./update-stack.sh <stack-name-server> server.yml server-parameters.json
./update-stack.sh <stack-name-bastion-host> bastion-host.yml bastion-host-parameters.json
```

### Bastion Host

The Linux bastion host in one of the public subnets has an Elastic IP address to allow inbound Secure Shell (SSH) access to EC2 instances in public and private subnets. A security group for fine-grained inbound access control. Update the parameter `RemoteAccessCIDR` to configure the allowed bastion external access CIDR.

## Requirements

Graded according to the [Project Rubric](hhttps://review.udacity.com/#!/rubrics/2556/view).

## License

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © [Thomas Weibel](https://github.com/thom).
