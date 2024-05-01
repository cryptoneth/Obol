(https://holesky.launchpad.obol.tech/



for pkg in docker.io docker-doc docker-compose docker-compose-v2 podman-docker containerd runc; do sudo apt-get remove $pkg; done


sudo apt-get update

sudo apt-get install ca-certificates curl


sudo install -m 0755 -d /etc/apt/keyrings

sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc

sudo chmod a+r /etc/apt/keyrings/docker.asc

echo \ 
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \ 
  $(. /etc/os-release && echo "$VERSION_CODENAME") stable" | \ 
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/nul 


sudo apt-get update

sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin

apt install git-all


git clone https://github.com/ObolNetwork/charon-distributed-validator-node.git

cd charon-distributed-validator-node

mkdir .charon

sudo chmod -R 777 .charon


docker run --rm -v "$(pwd):/opt/charon" obolnetwork/charon:v0.19.1 create enr

تا این مرحله برای گرفتن 
ENR 
بود

-------------------------------------------


apt install screen

apt install docker-compose

screen -S obol

cd charon-distributed-validator-node

sudo apt upgrade docker

sudo apt upgrade docker-compose

docker compose up -d


اگر سالم بود هیچی

---------------------------------

اگر خراب بود و ران نشد درست 

******change yml in your server 
اول فایل YML
رو تغییر بدید بعد کد های پایین رو بزنید

docker compose up -d

docker compose down

docker compose up -d

اینجا دیگه میبینید 8 تا 8 تا اجرایی شده


-------------------------------


https://docs.google.com/forms/d/e/1FAIpQLSdlrt-s5_CtJaebIbts3_p08mT_wo6ejbloBlgBmDWXspFa7Q/viewform


https://holesky.beaconcha.in/validators/deposits

https://holesky.beaconcha.in/


https://discord.com/invite/n6ebKsX46w?ref=blog.obol.tech

https://explorer.rated.network/)
