# ansible-roles


## Ubuntu 14.04 roles
* db_master
* db_replication
* db_slave
* deploy_code
* gunicorn
* nginx
* postgresql
* pyenv
* python

## Usage(to AWS)
> sudo ansible-playbook -u USERNAME --private-key AWS_KEY_NAME YML_FILE_NAME
### Example
* sudo ansible-playbook -u ubuntu --private-key junkyu.pem postgresql.yml
