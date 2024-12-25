Hello, 

i got a booting version for CB2 with newer kernel and "latest" (25.12.24) Armbian Version.

I dont take care if you use this Image its under your own risk!

First Download CB2 image https://drive.google.com/file/d/1ZcWxQnl73ZC4QlOMRiY9tBDAFCI9ZEce/view?usp=sharing
Burn Image to SD-Card
Open SD-Card on your Computer goto directory "root" and search for file "not logged in yet"

Open the file and change it to your settings that you need (Wifi/password/User etc.)
Save the file and put the Card in the Printer.

Wait about 2-3 mins to boot, you should see with a programm of your choice that there will be an IP address to where you can connect via SSH.

First you have to log in with root/1234

wait until terminal is refreshed then logout and login via user biqu pass biqu and now you have to manually install Klipper via Kiauh.

* **Step 1:** \
To download this script, it is necessary to have git installed. If you don't have git already installed, or if you are unsure, run the following command:
```shell
sudo apt-get update && sudo apt-get install git -y
```

* **Step 2:** \
Once git is installed, use the following command to download KIAUH into your home-directory:

```shell
cd ~ && git clone https://github.com/dw-0/kiauh.git
```

* **Step 3:** \
Finally, start KIAUH by running the next command:

```shell
./kiauh/kiauh.sh
```

* **Step 4:** \
You should now find yourself in the main menu of KIAUH. You will see several actions to choose from depending
on what you want to do. To choose an action, simply type the corresponding number into the "Perform action"
prompt and confirm by hitting ENTER.
