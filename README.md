OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES

tsh login --proxy=example.com

export aws_variables

ansible-playbook playbook.yml -e env=dev