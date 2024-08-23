





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
sudo apt install curl git wget htop tmux build-essential jq make lz4 gcc unzip gcc clang cmake build-essential -y
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

- https://train.flock.io/stake adresine gidelim validator seçelim cüzdan bağladıktan sonra github bağlıyoruz. ve otomatik 30 adet geliyor zaten minimum stake miktarı bu
- görev seçiyoruz. 30fml yazıyoruz approve ettikten sonra stake ediyoruz uyarılarda gpu dior ama resimelrde göreceğiniz üzere cpu da destekliyor. sağda confir demenizde gerekiyor çıkan uyarıya

![image](https://github.com/user-attachments/assets/71fc3f68-a951-4e57-8746-be49f1640bb1)


![image](https://github.com/user-attachments/assets/13e7e495-1373-4d84-a7f8-eed38a9f21b6)

![image](https://github.com/user-attachments/assets/639287f2-3353-4284-9dcc-2c7446da4b6e)

![image](https://github.com/user-attachments/assets/2b40ecf6-fd46-4842-9e33-0598aa1ebaa7)

![image](https://github.com/user-attachments/assets/39dd6230-4cd2-4288-ab7f-aebf72ec6b37)


#### Aşama 2

- API keyimizi alalım sağ yukardan cüzdana tıkla api yazıyor tıklayıp api sayfasına geçelim ordaki bilgileri alalım ve bir metin belgesine kaydedelim

![image](https://github.com/user-attachments/assets/680603b2-462f-4004-aa2d-d66d5b64ec09)

#### Aşama Misson imposible

- https://huggingface.co/ adresine gidip üye olalım. mail doğrulayalım
- sağ menüden settinge gelin
- access tokene gelin.
- sağdaki seçenekten create token deyin yetkileri ayarlayın. ve oluşturun
- çıkan keyi kaydedelim.

#### Aşama 3
```
cd
git clone https://github.com/FLock-io/llm-loss-validator.git
cd llm-loss-validator
```
```
conda create -n llm-loss-validator python==3.10
```
NOT: yeni güncellenen paketler var yes diyelim
```
conda activate llm-loss-validator
```
```
pip install -r requirements.txt

```
NOT: aşağıya  api keyimizi yazıyoruz. siteden aldığımız. hugginden aldığımız ve yine flock io sitesinde stake etiğimizde sağda görev idsi yazıyor mesela resimde 10 görünüyor 10 yazıcan :D

![image](https://github.com/user-attachments/assets/29421eb5-3980-4033-87e1-3719c20cf974)

```
cd /src
```
```
bash start.sh \
--hf_token BURAYA-HUGGİNG-KEY-YAZ \
--flock_api_key BURAYA-FLOCK-API-KEY-YAZ \
--task_id BURAYA-ID-YAZ \
--validation_args_file validation_config_cpu.json.example \
--auto_clean_cache False
```

![image](https://github.com/user-attachments/assets/44cac1c1-ed09-4fac-8105-b7ce5e308cef)









