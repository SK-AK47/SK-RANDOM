
termux-setup-storage 

pkg update -y

pkg upgrade -y

pkg install git -y

pkg install python -y

pkg install python2 -y

python3 -m pip install --upgrade pip

pip install requests

pip install mechanize

pip install future

rm -rf SK-RANDOM

git clone https://github.com/SK-AK47/SK-RANDOM

cd SK-RANDOM
 
python SKKING.py 
