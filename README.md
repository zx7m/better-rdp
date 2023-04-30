# FREE RDP WINDOWS SERVER!

Create Free RDP 7GB RAM and 2 CPU Core with Github.
Follow these instructions

+ Click Fork to get started (Mobile users please activate Desktop Mode).
+ Visit https://dashboard.ngrok.com to get NGROK_AUTH_TOKEN
+ In this repository go to Settings> Secrets> New repository secret
+ Name: NGROK_AUTH_TOKEN
+ Value: https://dashboard.ngrok.com/auth/your-authtoken copy and paste authtoken in the value
+ Click add secret
+ Go to Actions (if you see any warning click "I understand...")
+ On the left, select your preferred OS.
+ On the right, select "Run workflow"
+ refresh the page and click on the running workflow
+ click build and wait
+ Click the down arrow "RDP INFO LOGIN" To get IP, User, Password. (WINDOWS ONLY, SEE "CONNECTING TO MAC RDP" FOR MAC)

## Connecting to a Mac RDP
### From your browser
+ click the TMate link in the build step
### From SSH
+ copy the ssh connection string into your terminal

## Connecting to the Windows RDP from Windows
+ Click the windows key
+ Search "RDP" or "Remote Desktop Connection"
+ Open the app
+ Put in the login info from the instructions
+ Connect

## Connecting to the Windows RDP from a Mac
+ Go to the App Store and install the [MacOS RDP Client](https://itunes.apple.com/app/microsoft-remote-desktop/id1295203466?mt=12)
+ Open the app
+ Put in the login info from the instructions
+ Connect

## Connecting to a Windows RDP from Linux
+ This isnt officially supported, but if you [install Remmina](https://remmina.org/how-to-install-remmina/) and [follow the tutorial](https://cat.pdx.edu/platforms/linux/remote-access/using-rdp-to-connect-to-a-windows-computer-from-linux/) you can connect.
