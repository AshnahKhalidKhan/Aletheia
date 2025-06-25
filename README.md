# Aletheia
_Real voices. Honest insights. Responsible AI._

**Where candor meets courtesy.**  
Aletheia is a review app targeted towards college and university students, dedicated to quick, clear, honest and respectful professor/course feedback. Its unique feature is its responsible AI moderation, which ensures that student reviews are candid, courteous, and free from offensive and excessively harsh language.

#### Anything beyond this point, you don't need to read in case you don't want to know how I did what I did.
- After the atrocity called Google-XYZ, I have decided to comment out these notes that I keep for myself because hey, no one else needs to know if they don't want to learn and just judge me for how I learn things. Badtameez log. Khair, keeping all this uncommented for now because no one is keeping tabs on me before this repository goes live.

- I understand that I need to have an app frontend and a backend. Actually, let me just go quickly stalk Aun's Chips project to see how an FYP level project app structure looks like. Be right back.

- Yeah, so that was useless. Let's start doing what we do best (not): research.

- We shall create two folders - `frontend` and `backend`. The `frontend` folder will be initialized using Flutter for which I need to download Flutter and set it up first. So let's do that before I create the folders and all.

- Steps to download Flutter on Windows which I'm referring to from this link [https://docs.flutter.dev/get-started/install/windows/mobile](https://docs.flutter.dev/get-started/install/windows/mobile):
    - Download Git.
    - Download Android Studio [https://developer.android.com/studio](https://developer.android.com/studio) (You will have to scroll down to the bottom for the links, and downloading it will take A LOT of time).
    - Download Visual Studio Code.
    - Download Flutter extension for VS Code.
    - Launch VS Code > Enter `Ctrl + Shift + P` to open the Command Palette > Type `flutter` > Select `Flutter: New Project` > Click `Download SDK` > Navigate to `C:\Flutter` (Make the folder if you have to) > Click `Clone Flutter` (in case something goes wrong, just do the download thing again) > Terminal will open with a lot of progress messages > Click `Add SDK to PATH` > Click `Locate SDK` > Navigate to `C:\Flutter\flutter` > Click `Locate SDK` > You will later be prompted for `Which Flutter template?`, so just press Esc to exit it.
    - Launch Android Studio > Follow the Android Studio Setup Wizard going with all default selected settings > Select `Standard` installation > Click `Accept` > Install the following components:
        - Android SDK Platform, API 35
        - Android SDK Command-line Tools
        - Android SDK Build-Tools
        - Android SDK Platform-Tools
        - Android Emulator
    - You need to enable VM acceleration on your device, so to do so go to the Windows search bar > `Turn Windows features on or off` > Check the checkbox against `Windows Hypervisor Platform` and `Virtual Machine Platform` > OK > Once the installation has finished, **restart your computer**. 
    - Start Android Studio > `More actions` > `Virtual Device Manager` > Click on the `+` sign on the top-left to add a device > Select `Phone` and `Medium Phone` (just because - I don't know bro) > `Next` > Under `System Image`, select the one that has `x86` in it > `Additional settings` > Under `Enhanced Performance`, click `Preferred ABI` > `x86_64` > `Finish` > `Yes` > Wait for it to download > `Finish` > Click on the run/play icon next to the created device's name.
    - On VS Code, open a new terminal with elevated privileges using `Ctrl + Shift +` \` > Run `flutter doctor --android-licenses` > Enter `y` as many times as needed to accept all needed licenses.
    - Download or open `Visual Studio Installer` > `Modify` > Tick `Desktop development with C++` > On the right-hand side checklist, tick `C++ CMake tools for Windows`, `Windows 10 SDK (10.0.20348.0)` (or higher version) and `MSVC v142 - VS 2019 C++ x64/x86 build tools` > `Modify` > Once the installation has finished, **restart your computer**.
    - Open PowerShell with Run As Administrator > Run `flutter doctor -v` > everything should be good.

- Is it just me or did application development use to be so much more easier back when all this was just a course? Weird.

- It is so easily to 'realize', so easy to 'get', so easy to 'read' people; it is so dfficult, and often forgotten, to truly _understand_ someone.

- 
