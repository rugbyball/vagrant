ref: http://stackoverflow.com/questions/9434313/how-do-i-associate-a-vagrant-project-directory-with-an-existing-virtualbox-vm


For Vagrant 1.6.3 do the following:<br/ >

1) In the directory where your Vagrantfile is located, run the command<br/ >

VBoxManage list vms<br/ >
You will have something like this:<br/ >

"virtualMachine" {xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}<br/ >
2) Go to the following path:<br/ >

cd .vagrant/machines/default/virtualbox<br/ >
3) Create a file called id with the ID of your VM xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx<br/ >

4) Save the file and run vagrant up<br/ >
