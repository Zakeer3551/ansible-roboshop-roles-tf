This repo is for using/integrating with terraform remote-exec. 

You can invoke remote-exec in terraform and in the bootstrap.sh script it will install ansible first and move to ec2-user home direcotry and there it runs the ansible playbooks wrt each component.