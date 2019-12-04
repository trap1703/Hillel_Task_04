# Hillel_Task_04

Create a playbook:​

Update and upgrade yum-based Linux​
Install Java 8 (or other version)​
Create system tomcat user and group and Change ownership of Tomcat installation​
Install and configure tomcat​
Creates tomcat server user (use template file for this)​
<user username="{{ admin_username }}" password="{{ admin_password }}" roles="manager-gui" /> -- example entry​
You should use handler to restart tomcat, inventory (preferred), vars​
Start and enable tomcat and use wait_for module to wait for tomcat to start
