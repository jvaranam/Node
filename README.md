# Node
Multiple Node JS Versions with n

‘n’ can be installed using npm simply by running the following command. Depending on your operating systems and permissions, you might require sudo in front of.

"npm install -g n"

After installing n, you can switch between different versions of NodeJS installations as follows. If you don’t have the requested version installed on your machine, n will automatically download it, install it and then will switch the version.

"n 6.9.2"
"n 7.0.0"
"n stable" # this will install latest stable version of node
"n latest" # this will install the latest version of node

You can also list the install NodeJS versions in your machine running just n, and then you can graphically switch between the installed versions.

You can also dynamically change the NodeJS version for a particular application using n.
"n use 7.0.0 <filename>.js"
  
  
 If you are using Mac OS, you need to run following command. If ~/.bash_profile file is not there, you might need to create it first.
 
 While using "n" in mac use "sudo n 10.0.0" or use "sudo n stable" / "sudo n 12.13.0" which will change the node and npm version to the mentioned version. 
 
 "source ~/.bash_profile"
