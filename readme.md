# Before to run

```
export EC2_INI_PATH=ec2.ini
export AWS_ACCESS_KEY_ID='your access key'
export AWS_SECRET_ACCESS_KEY='your secret key'
```

Create ec2 instance with tag group=webservers

# running
```
ansible-playbook -i ec2.py site.yml
```