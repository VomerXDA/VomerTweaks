# VomerTweaks

# Introducing VomerTweaks!

# What is it?

VomerTweaks is a tried and tested set of custom settings and power modes for your device!
The aim is to enable your device to have insane battery life without losing performance.
We develop and test multiple configurations (for different "user types") & share them with the community.

# Who maintains it?

Look for these awesome folks on XDA Developers and send them a nice thank you:

@vomer / @JNewms / @The Gingerbread Man / @zephiK / @franciscofranco

# Donate

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=2TS9FDGD4462S&lc=CA&item_name=vomer%40xda&item_number=vomerxdadonation&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"><img src=https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif></a>

# Installation Instructions:

SETUP

1) Create a folder named <b>vomertweaks</b> on your internal storage. 

Note: the folder name should look exactly like it has been presented above (no caps)

2) Download and place ONE vomertweaks shell script (either DUAL or QUAD) into the folder made above

Example: /sdcard/vomertweaks/VomerTweaks_DualMode.sh

# APPLICATION (Pick One)

Method 1: init.d file application

1) Download the VomerTweaks init.d script installer & flash it in TWRP/CWM recovery

Note: Stock ROMs do not support init.d application. You will need to use: https://play.google.com/store/apps/details?id=com.androguide.universal.init.d

Method 2: Tasker Profile

You will need the Tasker app: https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en

Import the Tasker profile provided and turn it on.

Method 3: Manual application via Terminal

First, you will need this app: https://play.google.com/store/apps/details?id=jackpal.androidterm&hl=en

Note: If you use this method - the script needs to be re-applied manually on every reboot

Open the app and type this:

su
cd sdcard/vomertweaks
sh VomerTweaks_DualMode_N6.sh (switch script name to your chosen one)

# DOWNLOADS

VomerTweaks init.d script installer: http://bit.ly/1HbxfoP

VomerTweaks init.d script un-installer: http://bit.ly/1teD4cK

VomerTweaks Tasker Profile: http://bit.ly/1EC4zaC

Tweak Files (only Franco.Kernel is currently supported):

- Dual Mode (Keeps only 2 CPU cores active until you hit heavy CPU load) 
- Quad Mode (Keeps all 4 CPU cores active at all times)

Scripts: [url]http://bit.ly/1Bfnx0R[/url]

How do I check if the setting applied?

Get this app: https://play.google.com/store/apps/details?id=com.ryosoftware.cputweaks&hl=en

Check Max CPU - it should be under-clocked: 

<img src="http://i.imgur.com/iZECeF6.png">

# Additional Recommendations:

Franco Kernel Updater: https://play.google.com/store/apps/details?id=com.franco.kernel&hl=en

Per-App Modes: https://play.google.com/store/apps/details?id=com.franco.perappmodes&hl=en
