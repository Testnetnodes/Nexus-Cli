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

Çıkan ekranda 2 ye basıp devam ediyoruz

![image](https://github.com/user-attachments/assets/4cb30ec4-7ca1-42fd-95d6-23b523818c11)

Bizden node id'mizi isteyen onun içinde https://app.nexus.xyz/ siteye gidip,cüzdanımızla giriş yapıyoruz.Daha sonra Kırmızı kutunun içindeki Nodes kısmına basıp Add node dedikten sonra CLI bilgimizi almamız gerekiyor

![image](https://github.com/user-attachments/assets/ca8583bf-f095-4d1a-8d6d-34ba664cd4fc)

Daha sonradan,aldığımız CLI adresimi diyelimki 4252104,bu sayıyı sunucumuzda girip entera basıyoruz.

![image](https://github.com/user-attachments/assets/b56d6bfb-f7d2-47dc-aa87-5bdaa30c17b2)

Herşey yolunda gitmişse aşağıdaki gibi bi çıktı alacağız.

![image](https://github.com/user-attachments/assets/5e55f840-3113-442d-aa07-4bc921ddf47e)








