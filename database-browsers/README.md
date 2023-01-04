# Database Browsers
These are used to view the database from the browser. These are also using ingresses in order to access them. Both are secured by a username and a password that must be changed. You must change everything with a $ in front of the name. Please read through the yaml files if you need anything else that needs to be changed. Please note that phpMyAdmin will need a new DNS entry due to it not using path based routing. phpMyAdmin is also connecting to the specific mariadb Moodle sets up. You are able to change this if you want to connect a new db by setting this to false.

## To Install
Add the Helm repos and update:
```
helm repo add runix https://helm.runix.net/
helm repo add bitnami https://charts.bitnami.com/bitnami
helm update
```

Install using the yaml files:
```
helm install pgadmin runix/pgadmin4 -f pgadmin4.values.yaml
helm install phpmyadmin bitnami/phpmyadmin -f phpmyadmin.values.yaml
```