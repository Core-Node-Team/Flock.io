





<h1 align="center"> Flock.io

![image](https://github.com/user-attachments/assets/ce79ba5a-9c79-41d3-9f71-1124609ba9f8)



</h1>


 * [Topluluk kanalımız](https://t.me/corenodechat)<br>
 * [Topluluk Twitter](https://twitter.com/corenodeHQ)<br>
 * [Discord](https://discord.gg/XBGP8Ccgpm)<br>
 * [Twitter](https://twitter.com/flock_io)<br>
 * [Flock Website](https://www.flock.io/)<br>
 * [Flock Blog](https://www.flock.io/blog)<br>
 * [Flock gitbook/docs](https://docs.flock.io/)<br>
 * [Flock Telegram](https://t.me/flock_io_community)<br>



## 💻 Sistem Gereksinimleri
| Bileşenler | Minimum Gereksinimler | 
| ------------ | ------------ |
| CPU |	4|
| RAM	| 8+ GB |
| Storage	| 200 GB SSD |

### Gereklilikler
```
sudo apt-get update && sudo apt-get upgrade
sudo apt install curl git wget htop tmux build-essential screen jq make lz4 gcc unzip gcc clang cmake build-essential -y
```
```
sudo apt update && sudo apt install python3.10-venv python3-venv python3-pip
sudo apt-get update && sudo apt-get upgrade
```
```
wget https://repo.anaconda.com/archive/Anaconda3-2023.07-1-Linux-x86_64.sh
```
```
bash Anaconda3-2023.07-1-Linux-x86_64.sh
```

NOT: sayfanın aşağısına gelip yes yazıp enterla nereye kurayım diye soracak enterla. bidaha yes yazıp enterlıyacağız sorunca

![image](https://github.com/user-attachments/assets/1f082791-f464-4110-8bc3-cb83a5cea1ab)

```
source ~/.bashrc
```
```
conda list
```

Not: son kodu girince uzunca bir liste cıkıcak kuruldu.

![image](https://github.com/user-attachments/assets/3be89783-13c9-4007-a841-fb9da858d1a9)


### 👷 Başlangıç

#### Aşama 1

- https://train.flock.io/stake adresine gidelim training seçelim cüzdan bağladıktan sonra github bağlıyoruz. ve otomatik coin geliyor zaten minimum stake miktarı bu
- görev seçiyoruz. minimum miktarı yazıyoruz approve ettikten sonra stake ediyoruz uyarılarda gpu dior ama resimelrde göreceğiniz üzere cpu da destekliyor. sağda confir demenizde gerekiyor çıkan uyarıya



#### Aşama 2

- API keyimizi alalım sağ yukardan cüzdana tıkla api yazıyor tıklayıp api sayfasına geçelim ordaki bilgileri alalım ve bir metin belgesine kaydedelim

![image](https://github.com/user-attachments/assets/43ede330-e931-413d-b4be-b107b217d740)


#### Aşama Misson imposible

- https://huggingface.co/ adresine gidip üye olalım. mail doğrulayalım
- Sağ menüden settinge gelin

![image](https://github.com/user-attachments/assets/3e85fa05-2411-4714-9191-479ba2fcd63b)


- Access tokene gelin. sol menude 

![image](https://github.com/user-attachments/assets/d42290c7-f772-4aa1-a5c5-16e6d54f0086)


- Sağdaki seçenekten create token deyin yetkileri ayarlayın. ve oluşturun

![image](https://github.com/user-attachments/assets/83f73c5d-f818-48ed-8b51-2a2ac8b591d9)


![image](https://github.com/user-attachments/assets/57085311-9814-489b-9d62-3406cb41f43b)


- Cıkan keyi kaydedelim.
* Aşağıdaki yazanlar buyuk sunucuya kurulum yapacakalr içindir. lütfen dokumanın tamamını okuyun once.
- https://huggingface.co/mistralai/Mistral-7B-v0.3 adresine gidin agrre diyerek ana ekrande kullanım yetkisi alın.
- https://huggingface.co/google/gemma-2b adresine gidin agrre diyerek ana ekrande kullanım yetkisi alın.
- https://huggingface.co/google/gemma-7b adresine gidin agrre diyerek ana ekrande kullanım yetkisi alın.
- Mubarek uganda cumhurbaşkanı koruma görevlisi işe alım formu :D

![image](https://github.com/user-attachments/assets/aab68993-686f-43bc-bac3-066fb5853fb3)


#### Aşama 3
```
cd
git clone https://github.com/FLock-io/testnet-training-node-quickstart.git
cd testnet-training-node-quickstart
```
```
conda create -n training-node python==3.10
```
NOT: yeni güncellenen paketler var yes diyelim
```
conda activate training-node
```
```
pip install -r requirements.txt

```

#### Aşama 4
NOT: Screen içinde çalıştıralım. aşağıdaki kodla açıyoruz çıkarken `ctrl+ad` tekrar girmek için `screen -r flock`
```
screen -S flock
```
```
cd
cd testnet-training-node-quickstart
conda activate training-node
```
> Başlatalım.
```
TASK_ID=BURAYA-TAS-ID-YAZ FLOCK_API_KEY="FLOCK-API-YAZ" HF_TOKEN="<your-hf-token>" HF_USERNAME="BURAYA-HUGGİNG-UYE-OLUNAN-ADI-YAZ" python full_automation.py
```

# Faydalı Linkler

## [Komutlar](https://github.com/Core-Node-Team/CosmosSDK-Node/blob/main/Ortak-Komutlar.md)
## [Node Yedekleme ve Taşıma](https://github.com/Core-Node-Team/CosmosSDK-Node/blob/main/Yedekleme%20ve%20Ta%C5%9F%C4%B1ma.md)
## [Port Değiştirme](https://github.com/Core-Node-Team/CosmosSDK-Node/blob/main/Port%20de%C4%9Fi%C5%9Ftirme.md)
## [Sync-Peer-FAQ](https://github.com/Core-Node-Team/Cosmos-Aglarinda-Node-Calistirmak/blob/main/Sync-Peer%20Nedir.md)


<div align="center">

# Core Node 

#  [Twitter](https://twitter.com/corenodeHQ)|[Discord](https://discord.gg/fzzUAU9k)|[Telegram](https://t.me/corenodechat)  

![1500x500](https://github.com/Core-Node-Team/Testnet-TR/assets/108215275/92b50dd4-8043-4500-b906-bc8d15b75525)

## Sorularınız olursa Telegram Sohbet Grubumuz Ve Discord Sunucumuza Katılabilirsiniz.
#


