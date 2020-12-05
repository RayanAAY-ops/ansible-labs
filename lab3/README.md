1• Return to a blank file named `storage.txt` informations about  hosts hostname.

2• Create custom facts for `firewalld` with facts about: `package`,`service`,and `state = stopped`

3• run `ansible all -m setup -a "filter = ansible_local"` to verify your results.


