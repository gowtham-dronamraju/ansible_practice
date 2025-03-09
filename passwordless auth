ansible practice

Connect AWS instances 
ssh using 
1. eval $(ssh-agent)
2. ssh-add /home/gowtham/gowtham-aws-keypair.pem
3. ssh-copy-id -f "-o IdentityFile <PATH TO PEM FILE>" ubuntu@<INSTANCE-PUBLIC-IP>

       ssh-copy-id -f "-o IdentityFile /home/gowtham/gowtham-aws-keypair.pem" ubuntu@52.91.113.202
     

e.g. ssh -o ' IdentityFile /home/gowtham/gowtham-aws-keypair.pem' 'ubuntu@52.91.113.202'


ssh -i <PATH TO PEM FILE>" ubuntu@<INSTANCE-PUBLIC-IP>
