ref: http://stackoverflow.com/questions/14733681/vagrant-d-outside-of-the-home-folder

setx VAGRANT_HOME "/d/.vagrant.d/"

D:\HashiCorp\Vagrant\embedded\gems\gems\vagrant-1.5.3\lib\vagrant\environment.rb
on line 117 to

@home_path = Util::Platform.fs_real_path("D:/vagrant/home/")

