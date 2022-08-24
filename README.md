# Counter_Flutter

Due to pandemic, there was a need to build an app just to count people in a room.

First of all, We need to install Flutter in our computer. See the documentation at https://flutter.dev/docs/get-started/install/linux and then,
We gonna use Snap Store after the Snapd had been installed.

So, We can use this command line below in the terminal as root administrator:
sudo snap install flutter --classic

Then, We have to put this command line below in the terminal too:
sudo snap alias flutter.dart dart

After that, We also have to put this command line below in the terminal:
sudo snap install android-studio --classic

Finally, execute the command line:
flutter

And more information and packages will be install too.

Once again, We should put the command line below after all of that, just to check if there is some error or something went wrong:
flutter doctor

FYI: Probably something went wrong with the Android-Studio, so We should find this Software in our computer and then;
Do not import settings => ok
Data Sharing => Do not send
Welcome => Press Next button
Install Type => Press Next button
Select UI Theme => Dark Theme => Press Next button
Verify Settings => Press Next button
Emulator Settings => Press Finish button
Downloading Components

Once again, We should put the command line below after all of that, just to check if there is some error or something went wrong again:
flutter doctor

Exception: flutter config --android-studio-dir /snap/android-studio/current/android-studio

To accept the licenses, we have to excecute these commands below:
flutter doctor --android-licenses

Maybe there is an error, so We should open the Android-Studio Software once again, select the option More Actions, SDKManager, SDKTools, Android SDKCommand-line Tools(latest) => Apply => OK => Accept => Next => Finish => OK

Then, execute one more time this command line:
flutter doctor --android-licenses
press the y (yes) button to accept all the licenses for six times.

Finally, execute the command line (only):
flutter doctor

With the Android-Studio Software opened, we have to install the plugins.
Press the button Plugins on the left, type flutter on search and then click on Install button => Accept => Install Required Plugins including Dart => Install => Restart IDE

On Android-Studio Software
open this software on research tab in the computer => Select this option Projects on the left tab => New Flutter Project => Select Flutter on the left tab => Next button => Project Name (counter_flutter2) => Project Location (~/Área de Trabalho/Counter_Flutter/counter_flutter2) => Description (Whatever) => Project Type Application => Organization (Whatever) => Android Language Kotlin => IOS Language Swift => Platforms: Android - IOS - Web => Finish button => Create button

On VSCODE
We can install some plugins like Commands Palette:
with VSCODE opened, on the View tab, Command Palette (Ctrl + Shift + P) => Install on the search tab => Extensions: Install Extensions => on the left we should research for Flutter => click on Flutter => click on Installing => Command Palette (Ctrl + Shift + P) => type doctor => select this option => probably something went wrong with environment variables => or everything went right

---

---

To get an Emulator
press the button Device Manager on right top of the screen. Select the option Create Virtual Device, and then choose Phone on left top tab.
After that, choose one that contains Play Store like Nexus 5x, so press the button Next. About the Android Version, it is a good idea to choose the latest one. So We can let the Portrait option and then press the Finish button. Press twice on it to execute it right away.
Inside the Menu => Settings => Emulator Always on Top

In the physical device (smartphone) We can test our application doing the next steps:
researching for USB Depuration / Debugging and then activate it. We can get through Developer Options => USB Debugging.

For Dart Language, We can practice or develop our codes by https://dartpad.dev/?

save location: /home/alunime/AndroidStudioProjects/Counter_Flutter
flutter SDK path: /home/alunime/snap/flutter/common/flutter
git add README.md
git commit -s -m "Add README base file"
git push
