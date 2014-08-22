dashboard
=========

a dashboard based on node.js, dashing-js, npm


about node.js:
http://www.youtube.com/watch?v=GJmFG4ffJZU

http://howtonode.org/how-to-install-nodejs

npm:
https://github.com/npm/npm


1. node.js is installed 
   Add variable to PATH in csh environmentvariable
   setenv PATH $PATH\:/home/eclaeis/stuff/github/node

2. npm is installed
3. 


echo 'export PATH=$HOME/local/bin:$PATH' >> ~/.bashrc
. ~/.bashrc
mkdir ~/local
mkdir ~/node-latest-install
cd ~/node-latest-install
curl http://nodejs.org/dist/v0.10.9/node-v0.10.9-linux-x64.tar.gz | tar xz --strip-components=1
./configure --prefix=~/local
make install # ok, fine, this step probably takes more than 30 seconds...
curl https://www.npmjs.org/install.sh | sh
