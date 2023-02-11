rpi-rw

sudo cp -p /usr/local/bin/ircddbgatewayd /usr/local/bin/ircddbgatewayd-bkp

sudo rm /usr/local/bin/ircddbgatewayd

sudo git clone https://github.com/pu4ron/ircddbgateway2023.git

cd ircddbgateway2023

sudo cp ircddbgatewayd /usr/local/bin

sudo chmod 777 /usr/local/bin/ircddbgatewayd
