This play create 3 users: alice, bob and carol with passwords alicepassword, bobpassword and carolpassword accordingly.
Encrypted users data stored in vars/users. Vault pass in file pass_file

ansible-playbook --vault-password-file=pass_file playbook1.yml
