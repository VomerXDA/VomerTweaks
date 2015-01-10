# VomerTweaks

# Introducing VomerTweaks!

# What is it?

VomerTweaks is a tried and tested set of custom settings and power modes for your device!
The aim is to enable your device to have insane battery life without losing performance.
We develop and test multiple configurations (for different "user types") & share them with the community.

# Who maintains it?

Look for these awesome folks on XDA Developers and send them a nice thank you:

@vomer / @JNewms / @The Gingerbread Man / @zephiK / @franciscofranco

[B][COLOR="DeepSkyBlue"]# Donate[/COLOR][/B]

[URL="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=2TS9FDGD4462S&lc=CA&item_name=vomer%40xda&item_number=vomerxdadonation&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"][IMG]https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif[/IMG][/URL]

[B][COLOR="DeepSkyBlue"]# Installation Instructions:[/COLOR][/B]

[B]SETUP[/B]

1) Create a folder named [B]vomertweaks[/B] on your internal storage. 

[I]Note: the folder name should look exactly like it has been presented above (no caps)[/I]

2) Download and place ONE vomertweaks shell script (either DUAL or QUAD) into the folder made above

[I]Example: /sdcard/vomertweaks/VomerTweaks_DualMode.sh[/I]

[B]APPLICATION (Pick One)[/B]

[B]Method 1: init.d file application[/B]

1) Download the VomerTweaks init.d script installer & flash it in TWRP/CWM recovery

Note: Stock ROMs do not support init.d application. You will need to use [URL="https://play.google.com/store/apps/details?id=com.androguide.universal.init.d"]this app[/URL]

[B]Method 2: Tasker Profile[/B]

You will need the Tasker app: [url]https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm&hl=en[/url]

Import the Tasker profile provided and turn it on (how-to: [url]http://tasker.dinglisch.net/userguide/en/faqs/faq-how.html#q[/url])

[B]Method 3: Manual application via Terminal[/B]

First, you will need this app: [url]https://play.google.com/store/apps/details?id=jackpal.androidterm&hl=en[/url]

Note: If you use this method - the script needs to be re-applied manually on every reboot

Open the app and type this:

[CODE]su
cd sdcard/vomertweaks
sh VomerTweaks_DualMode_N6.sh (switch script name to your chosen one)
[/CODE]

[B][COLOR="DeepSkyBlue"]# Downloads:[/COLOR][/B]

VomerTweaks init.d script installer: [url]http://bit.ly/1HbxfoP[/url]

VomerTweaks init.d script un-installer: [url]http://bit.ly/1teD4cK[/url]

VomerTweaks Tasker Profile: [url]http://bit.ly/1EC4zaC[/url]

[B]Tweak Files[/B] ([COLOR="red"]only Franco.Kernel is currently supported[/COLOR]):

[LIST]
[*]Dual Mode (Keeps only 2 CPU cores active until you hit heavy CPU load) 
[*]Quad Mode (Keeps all 4 CPU cores active at all times)
[/LIST]

- Scripts: [url]http://bit.ly/1Bfnx0R[/url]

[B]How do I check if the setting applied?[/B]

Get this app: [url]https://play.google.com/store/apps/details?id=com.ryosoftware.cputweaks&hl=en[/url]

Check [URL="https://i.imgur.com/60j6SXS.png"]Max CPU[/URL] - it should be under-clocked.

[B][COLOR="DeepSkyBlue"]# Additional Recommendations:[/COLOR][/B]

- [URL="https://play.google.com/store/apps/details?id=com.franco.kernel&hl=en"]Franco Kernel Updater[/URL]
- [URL="https://play.google.com/store/apps/details?id=com.franco.perappmodes&hl=en"]Per-App Modes[/URL]
