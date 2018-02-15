# one-node
Download this repository 
extract one-node-master folder and open terminal there


sudo apt-get install libleveldb-dev sqlite3 libsqlite3-dev curl

curl https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg
sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/microsoft-ubuntu-xenial-prod xenial main" > /etc/apt/sources.list.d/dotnetdev.list'

sudo apt-get install apt-transport-https

sudo apt-get update

sudo apt-get install dotnet-sdk-2.1.4


sudo dotnet neo-cli.dll --rpc



open wallet  walletname.db3
enter password


start consensus






