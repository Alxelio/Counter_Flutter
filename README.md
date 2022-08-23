# Counter_Flutter

Due to pandemic, there was a need to build an app just to count people in a room.

First of all, We need to install Flutter in our computer. See the documentation at https://flutter.dev/docs/get-started/install/linux and then,
We gonna use Snap Store after the Snapd had been installed.

So, We can use this command line below in the terminal as root administration:
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
Press the button Plugins on the left, type flutter on search and then click on Install button => Accept => Install Required Plugins => Install => Restart IDE

On VSCODE
We can install some plugins like Commands Palette:
with VSCODE opened, on the View tab, Command Palette (Ctrl + Shift + P) => Install on the search tab => Extensions: Install Extensions => on the left we should research for Flutter => click on Flutter => click on Installing => Command Palette (Ctrl + Shift + P) => type doctor => select this option => probably something went wrong with environment variables => or everything went right
