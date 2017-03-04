# Object Detection

python object detection using cv2 (opencv)

## Installation
### prerequesits
osx - brew install --force opencv3  --with-java --with-python3 --with-contrib --with-ffmpeg --with-qt5
###$ linux 
sudo apt-get update
sudo apt-get install git
#install python3.5.2 from source
#http://raspberrypi.stackexchange.com/questions/54365/how-to-download-and-install-python-3-5-in-raspbian

cd ~
mkdir -p apps 
cd apps

###  clone & setup
git clone git@github.com:codeinvain/object_detection.git

cd object_detection

python3 -m venv .pip

for Mac
source .pip/bin/activate

pip3 install -U

for Windows
 ./.pip/Scripts/Activate.bat

 pip install -r requirements.txt

## Run application
bin/tracks 


