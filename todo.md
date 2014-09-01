TODO
_______________

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
      ______________________________________________________________________________________________________________

      echo 'export PATH=$HOME/local/bin:$PATH' >> ~/.bashrc

      source ~/.bashrc

      mkdir ~/local

      mkdir ~/node-latest-install

      cd ~/node-latest-install

      curl http://nodejs.org/dist/v0.10.9/node-v0.10.9-linux-x64.tar.gz | tar xz --strip-components=1

      ./configure --prefix=~/local

      make install # ok, fine, this step probably takes more than 30 seconds...

      curl https://www.npmjs.org/install.sh | sh

      _____________________________________________________________________________________________________________________
      echo PATH=$HOME/local/bin:$PATH
      PATH=/home/eclaeis/local/bin:.../home/eclaeis/stuff/github/bin/npm:/home/eclaeis/stuff/github/node

      echo 'export PATH=$HOME/local/bin:$PATH' >> ~/.bashrc
      puts them all in the bashrc
      
      
      
 -------------------------------------------------------------------------
eclaeis@esekiws5163 [stuff/github/dashing-js]: npm install -g dashing-js
npm WARN engine hawk@0.10.2: wanted: {"node":"0.8.x"} (current: {"node":"0.10.31","npm":"1.4.23"})
npm WARN engine sntp@0.1.4: wanted: {"node":"0.8.x"} (current: {"node":"0.10.31","npm":"1.4.23"}) 
npm WARN engine cryptiles@0.1.3: wanted: {"node":"0.8.x"} (current: {"node":"0.10.31","npm":"1.4.23"})
npm WARN engine hoek@0.7.6: wanted: {"node":"0.8.x"} (current: {"node":"0.10.31","npm":"1.4.23"})     
npm WARN engine boom@0.3.8: wanted: {"node":"0.8.x"} (current: {"node":"0.10.31","npm":"1.4.23"})     
npm WARN excluding symbolic link test/fixtures/app/views/.#application.js.coffee.erb -> sam@pursuit.41266
\                                                                                                        
> node-sass@0.7.0 install /home/eclaeis/local/lib/node_modules/dashing-js/node_modules/node-sass         
> node build.js                                                                                          

`linux-x64-v8-3.14` exists; testing
    
      
      
        16 passing (43ms)

Binary is fine; exiting
/home/eclaeis/local/bin/dashing-js -> /home/eclaeis/local/lib/node_modules/dashing-js/bin/dashing-js
dashing-js@0.1.5 /home/eclaeis/local/lib/node_modules/dashing-js
ттт commander@2.1.0
ттт express-ejs-layouts@0.3.1
ттт consolidate@0.10.0
ттт async@0.2.10
ттт node-schedule@0.1.13
ттт fs-extra@0.8.1 (jsonfile@1.1.1, rimraf@2.2.8, ncp@0.4.2, mkdirp@0.3.5)
ттт ejs@0.8.8
ттт walker@1.0.6 (makeerror@1.0.8)
ттт coffee-script@1.6.3
ттт request@2.30.0 (json-stringify-safe@5.0.0, aws-sign2@0.5.0, forever-agent@0.5.2, qs@0.6.6, tunnel-agent@0.3.0, oauth-sign@0.3.0, mime@1.2.11, node-uuid@1.4.1, form-data@0.1.4, tough-cookie@0.9.15, http-signature@0.10.0, hawk@1.0.0)
ттт unzip@0.1.9 (setimmediate@1.0.2, readable-stream@1.0.31, match-stream@0.0.2, pullstream@0.4.0, fstream@0.1.31, binary@0.3.0)
ттт prompt@0.2.13 (revalidator@0.1.8, pkginfo@0.3.0, read@1.0.5, utile@0.2.1, winston@0.6.2)
ттт winston@0.7.3 (stack-trace@0.0.9, cycle@1.0.3, eyes@0.1.8, colors@0.6.2, pkginfo@0.3.0, request@2.16.6)
ттт mincer@0.5.13 (shellwords@0.1.0, fs-tools@0.2.11, mimoza@0.3.0, hike@0.1.4, lodash@2.4.1, argparse@0.1.15)
ттт jade@0.35.0 (character-parser@1.2.0, commander@2.0.0, mkdirp@0.3.5, with@1.1.1, constantinople@1.0.2, transformers@2.1.0, monocle@1.1.50)
ттт express@3.4.8 (methods@0.1.0, merge-descriptors@0.0.1, debug@0.8.1, cookie-signature@1.0.1, range-parser@0.0.4, fresh@0.2.0, buffer-crc32@0.2.1, cookie@0.1.0, mkdirp@0.3.5, send@0.1.4, commander@1.3.2, connect@2.12.0)
ттт node-sass@0.7.0 (node-watch@0.3.4, colors@0.6.0-1, mkdirp@0.3.5, optimist@0.6.1, mocha@1.13.0)
eclaeis@esekiws5163 [stuff/github/dashing-js]:
eclaeis@esekiws5163 [stuff/github/dashing-js]:

      

