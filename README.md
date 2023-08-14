# mintgoldtoken
## spl-token-minter like program built using solidity(solang) 

## How to Run this program

**First setup system requirements using this link-> blog link

**Clone this repo**  

``
git clone git@github.com:shivamsoni00/mintgoldtoken.git
``

go to root directory  

``
cd mintgoldtoken
``

create a file named yarn.lock using this command and install yarn

``
touch yarn.lock  
``  

``
yarn install
``

run this command for package files updates 

``
pnpm install
``  

create a file named .yarnrc.yml  

``
touch .yarnrc.yml
``  

add this line in this file  
nodeLinker: node-modules  

## For building program  

setup your solana wallet location 
in anchor.toml file  

after run this command  

``
anchor build
``  

open new terminal window and run   

``
solana-test-validator
``  

now run  

``
anchor deploy
``  

grab programId and edit it in .sol(solana program file)  
and anchor.toml file  

then run again  

``
anchor build
``  

running test  
check your current wallet address and balance using  

``
solana address  
``

``
solana balance
``

now run  

``
anchor test
``








