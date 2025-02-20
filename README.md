# Nexus-Cli

sudo apt remove protobuf-compiler -y

curl -LO https://github.com/protocolbuffers/protobuf/releases/download/v27.3/protoc-27.3-linux-x86_64.zip

apt install unzip

unzip protoc-27.3-linux-x86_64.zip -d /usr/local

chmod +x /usr/local/bin/protoc


echo $PATH
echo 'export PATH="$PATH:/usr/local/bin"' >> ~/.bashrc
source ~/.bashrc

export PROTOC=/usr/local/bin/protoc

echo 'export PROTOC=/usr/local/bin/protoc' >> ~/.bashrc
source ~/.bashrc

curl https://cli.nexus.xyz/ | sh
