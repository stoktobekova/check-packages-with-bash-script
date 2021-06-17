# Create bash script to check all packages installed #296
```
#Hello Team! 
In this project the bash script checks if all the necessary packages are installed in bastion host every time when bastion host reloaded, 
otherwise all packages were checked manually. If one of the packages is not installed script should say package_name is not installed. 

To use this script use this link bellow please:
"https://github.com/stoktobekova/check-packages-with-bash-script.git"

### To run this command, we need to run the following command:
bash check-packages.sh

This script used to check the following packages in the bastion host: packer, terraform, kubectl, docker-compose, docker, helm, python3, tree, curl, wget, java, groovy,  waypoint, nslookup. 
The output of bash script commnad should look similar to this: 
$ packer is installed
$ terraform is installed
$ kubectl is not installed if kubectl is not installed etc.

Special thanks to Farhod!
```

