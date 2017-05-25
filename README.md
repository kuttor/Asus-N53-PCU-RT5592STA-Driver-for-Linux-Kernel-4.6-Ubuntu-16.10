# Asus-N53-PCU-RT5592STA-Driver-for-Linux-Kernel-4.6-Ubuntu-16.10
Asus-N53-PCU-RT5592STA-Driver-for-Linux-Kernel-4.6-Ubuntu-16.10


### Installation
- sudo git clone https://github.com/kuttor/Asus-N53-PCU-RT5592STA-Driver-for-Linux-Kernel-4.6-Ubuntu-16.10.git /opt/asus-n53-driver
- cd /opt/asus-n53-driver
- sudo make
- sudo make install
- sudo modprobe rt5592sta

### Troubleshooting
- I had to bring the wireless interface down and up and then restart NetworkManager for it to work. 
1. sudo ip link set enp2s0 down
2. sudo ip link set enp2s0 up
3. sudo systemctl restart enp2s0

