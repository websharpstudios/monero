# How to upgrade to version 18

git clone --recurse-submodules https://github.com/websharpstudios/monero 

git clone --recurse-submodules https://github.com/monero-project/monero ./monero17

cd monero

git checkout release-v18

make debug

.....

unit test

.....

make install # ONLY AFTER YOUR OLD WALLET HAS MONEY IN IT 

