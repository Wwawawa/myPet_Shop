# pet-shop
**_安装部署文档_**

http://blog.csdn.net/zxs9999/article/details/79155163

Email:  zxs@163.com


AS you need to environment:

	1- node.js
	2- npm
	3- npm install -g ethereumjs-testrpc
	4- npm install -g truffle@4.1.4
	5- MetaMask
	6- npm install -g lite-server

As you need to commend:
1- download code
2- testrpc --network-id 1337
3- truffle-config: need to configuration: detail as this file
4- truffle compile
5- truffle migrate
6- truffle test: if success
7- metaMask
8- truffle console
9- web3.eth.sendTransaction( {from :web3.eth.accounts[1], to: "0x20F686f7CdF7e31DB8742584E9efb5773D17C56d", value: web3.toWei("10","ether")})
10- npm run dev