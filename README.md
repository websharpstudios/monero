# Version 18 unit testing

git clone --recurse-submodules https://github.com/websharpstudios/monero 

git clone --recurse-submodules https://github.com/monero-project/monero ./monero17

cp -R ./monero17 ./monero

sudo rm -f ./monero17/.git

cd monero

git checkout release-v18

make debug

.....

unit test

.....

 # AFTER OLD WALLET HAS MONEY IN IT 
 
 make install
 
 git push v18
 
 # Wait 30 minutes for github confirmation of unit test

