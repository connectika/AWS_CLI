# AWS CLI
Automated installation of AWS Command Line Interface


## Deploy:
> ansible-playbook deploy_all.yml -i hosts
> ansible-playbook roles/aws_cli/deploy_aws_cli.yml -i hosts

## Notes:
  - Will not install Java or Python
  - Will only setup AWS CLI
  - Use deploy_all.yml or an individual playbook
  - Set proxy settings in group vars and uncomment in playbooks if required
