# GL_homework7_8

In this task we create Ansible script that will harden users’ passwords by rejecting the ones that contain a username (this rule will enforce  for ‘root’ as well):
- Install the libpam-pwquality package on our system

  ``` role install_pwquality ```
  
- After installing the package, we need to edit the /etc/pam.d/common-password file to set the password requirements

  ``` role harden_users_passwords ```

![hw7_password](https://user-images.githubusercontent.com/105345932/212575152-3964a30d-2013-4f06-9481-d99f07cd14c1.png)

![hw7_8_playbook_screenshot](https://user-images.githubusercontent.com/105345932/212575162-5011a913-16ce-476c-9c7f-77da79960db7.png)
