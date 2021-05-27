mkdir -p ~/build && cd ~/build

git clone https://github.com/JimmyBastos/rtl8821CU.git

sudo dnf install dkms kernel-devel

cd rtl8821CU

sudo ./dkms-install.sh

