
https://www.youtube.com/watch?v=fzmW8IbstRY

go to your folder and open terminal

create .secret file
paste 12 seed phrase then save

sudo npm install -g truffle
truffle version
truffle init 
npm install --save-dev @openzeppelin/truffle-upgrades
npm install @truffle/hdwallet-provider


copy 2_deploy_contracts.js to "migrations" foler   
copy MomentCollection.sol to "contracts" folder
replace truffle-config.js 

truffle deploy --network matric