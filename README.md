# manage-linux-user
to run this ansible:
edit file inventory, adding the corresponding IP addresses and usernames for each server.
add corresponding public key of each user on keys/
then perform 
ansible-playbook -i inventory user-manage.yaml
