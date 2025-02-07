# social-fish
phishing 
git clone https://github.com/UndeadSec/SocialFish.git
sudo apt-get install python3 python3-pip python3-dev -y
If it fails to completely install run the failed files indivually that will workout better
parently the the virtual environment will be suitable for this process as its a mac and also a virtual machine 
python3 -m venv myenv       # Create a virtual environment
source myenv/bin/activate  # Activate it (Linux/macOS)
myenv\Scripts\activate     # Activate it (Windows)
pip3 install -r requirements.txt
cd SocialFish
python3 -m pip install -r requirements.txt
python3 SocialFish.py <Specify your Username> <Make up a Password>
