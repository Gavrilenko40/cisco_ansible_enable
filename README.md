In this playbook you can see - How to Connect your cisco IOS switch with enable mode, and send some commands to device.

In vars file you need to change your auth , etc..
vars.yamlvar_host: "{{ inventory_hostname }}"
var_port: YOUR_PORT
var_username: USER
var_password: PASS
var_transport: cli
var_authorize: yes
var_auth_pass: PASSWORD_FOR_ENABLE_MODE

