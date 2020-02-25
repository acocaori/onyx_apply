# onyx_apply


example:

ansible-playbook conf_onyx.yaml -i hosts -e "local_ip=10.7.156.109" -e "path=/var/tmp/onyx_apply/config.bin" -e "type=bin" -e "del_all_first=yes"



flags:

local_ip = the server where the configuration file is located on
path = full path to the configuration file
type = bin / text
del_all_first = delte all configuration before apply the new config
