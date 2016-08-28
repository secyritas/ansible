# ansible
My Ansible script collection

# iodine.yml
Used to provision EC2 instance to run Iodine and update DDNS records on Hurricane Electric. Requires these environment variables:

```
export AWS_ACCESS_KEY_ID=''
export AWS_SECRET_ACCESS_KEY=''
export HE_PASSWORD=''
```

To run, use this:

```
ansible-playbook iodine.yml --private-key swordfish.pem -u ubuntu
```
