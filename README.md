# yametrica
# Deploy YAMetrics and APPMetrics into group of hosts [yahosts] from inventory file: hosts
# The role yametrica executes by playbook : play_yametrica.yml
# In role affected: yametrica/defaultss/main.yml(encrypted)  yametrica/tasks/main.yml  yametrica/templates/
# ansible-playbook -i hosts play_yametrica.yml --ask-vault-pass
# --tags "update_script" (update main app script)  --tags "start_containers" (run docker containers for APPMetrica)
