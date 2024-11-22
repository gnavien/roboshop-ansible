# roboshop-ansible
ansible-pull -i localhost, -U https://github.com/gnavien/... frontentend.yml This command will be used to pull the command locally.


# To run all the component one by one the instructor had used the below method
# for component in frontend mongodb mysql redis rabbitmq catalogue user cart shipping payment ; do 
# ansible-playbook main.yml -e ansible_user=centos -e ansible_password=DevOps321 -e
# role_name=${component} -i ${component}-dev.navien.site,; done
check

