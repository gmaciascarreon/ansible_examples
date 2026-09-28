This repo is to create ansible examples



source /home/ec2-user/.venv/bin/activate 
export TLS_KEY=$(base64 -w0 /home/ec2-user/ansible_examples/demo.cer)
ansible-playbook Test_create_files/site.yml
