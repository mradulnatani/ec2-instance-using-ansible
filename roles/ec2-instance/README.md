# Ansible Role: ec2-instance
This Ansible role provisions an AWS EC2 instance.

## Variables
| Variable          | Description                         |
|------------------|---------------------------------|
| `aws_region`     | AWS region to launch instance  |
| `instance_type`  | Instance type (e.g., t2.micro) |
| `ami_id`         | AMI ID for the instance        |
| `key_name`       | AWS key pair name              |
| `security_group_id` | Security group ID          |
| `subnet_id`      | Subnet ID                      |

## Usage
Run the playbook:
```bash
ansible-playbook ec2_instance.yml
