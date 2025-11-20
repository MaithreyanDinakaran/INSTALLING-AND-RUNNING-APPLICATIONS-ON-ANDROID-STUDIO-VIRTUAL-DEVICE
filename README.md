## INSTALLING AND RUNNING APPLICATIONS ON ANDROID STUDIO DATE

## Step 1 - System Requirements

The required tools to develop Android applications are open source and
can be downloaded from the Web. Following is the list of software you
will need before you start your Android application programming.

Java JDK5 or later version

Java Runtime Environment (JRE)

6Android Studio

## Step 2 - Setup Android Studio

Android Studio is the official IDE for android application
development.It works based on IntelliJ IDEA, You can download the latest
version of android studio from Android Studio 2.2 Download, If you are
new to installing Android Studio on windows,you will find a file, which
is named as android-studio-bundle-143.3101438-windows.exe.So just
download and run on windows machine according to android studio wizard
guideline.

If you are installing Android Studio on Mac or Linux, You can download
the latest version from Android Studio Mac Download,or Android Studio
Linux Download, check the instructions provided along with the
downloaded file for Mac OS and Linux. This tutorial will consider that
you are going to setup your environment on Windows machine having
Windows 8.1 operating system. Installation So let's launch Android
Studio.exe,Make sure before launch Android Studio, Our Machine should
required installed Java JDK. To install Java JDK,take a references of
Android environment setup

<img width="796" height="619" alt="image" src="https://github.com/user-attachments/assets/b36a4847-cea4-4f5d-b649-9979bd6fb9bb" />

Once you launched Android Studio, its time to mention JDK7 path or later
version in androidstudio installer.
<img width="791" height="615" alt="image" src="https://github.com/user-attachments/assets/b247b2dc-ee2c-4cfb-9a3b-d7719a5ca871" />

Below the image initiating JDK to android SDK
<img width="796" height="622" alt="image" src="https://github.com/user-attachments/assets/ab165e57-1c57-4873-b6e0-f1f53688d06a" />


Need to check the components, which are required to create applications,
below the image hasselected Android Studio, Android SDK, Android Virtual
Machine and performance(Intel chip).
<img width="796" height="615" alt="image" src="https://github.com/user-attachments/assets/f6d33295-b6a1-4485-bec1-cc2f5abd4333" />


Need to specify the location of local machine path for Android studio
and Android SDK, below the image has taken default location of windows
8.1 x64 bit architecture.

<img width="803" height="617" alt="image" src="https://github.com/user-attachments/assets/4ecb6136-e94a-4173-ad07-d939429212dd" />

Need to specify the ram space for Android emulator by default it would
take 512MB of localmachine RAM.

<img width="797" height="624" alt="image" src="https://github.com/user-attachments/assets/eb84c6b6-b926-474d-a080-fabf760424e6" />

At final stage, it would extract SDK packages into our local machine, it
would take a while time to finish the task and would take 2626MB of Hard
disk space.

<img width="795" height="624" alt="image" src="https://github.com/user-attachments/assets/5e95fa27-02fe-4ee9-9f8e-ba640cfb3e9a" />

After done all above steps perfectly, you must get finish button and it
gonna be open androidstudio project with Welcome to android studio
message as shown below

<img width="840" height="660" alt="image" src="https://github.com/user-attachments/assets/0a00e9b6-69e1-4d70-8c95-8f08b2071357" />

You can start your application development by calling start a new
android studio project. in a new installation frame should ask
Application name, package information and location of the project.
<img width="837" height="505" alt="image" src="https://github.com/user-attachments/assets/25b38d90-23a7-4482-93f4-4b63a1ea5118" />

<img width="844" height="573" alt="image" src="https://github.com/user-attachments/assets/84a98aad-bd37-48e6-ba1c-7a0370b74113" />

After entered application name, it going to be called select the form factors
your application runson,

here need to specify Minimum SDK, in our tutorial, I have declared as
API23: Android 6.0(Mashmallow)

<img width="847" height="579" alt="image" src="https://github.com/user-attachments/assets/e490216f-0a9d-42a8-ae0e-7f08e06c37e2" />
The next level of installation should contain selecting the activity to
mobile, it specifies the default layout for Applications

At the final stage it going to be open development tool to write the
application code.

## Step 3 - Create Android Virtual Device

To test your Android applications, you will need a virtual Android
device. So before we start writing our code, let us create an Android
virtual device. Launch Android AVD Manager Clicking AVD_Manager icon as
shown below
<img width="844" height="492" alt="image" src="https://github.com/user-attachments/assets/226186d2-4254-4a28-b260-b4be92428f14" />

After Click on a virtual device icon, it going to be shown by default
virtual devices which are present on your SDK, or else need to create a
virtual device by clicking Create new Virtual device button
<img width="844" height="355" alt="image" src="https://github.com/user-attachments/assets/9408aaad-7a8c-44c6-861e-a1a0ee5348ac" />

If your AVD is created successfully it means your environment is ready
for Android application development. If you like, you can close this
window using top-right cross button. Better you re- start your machine
and once you are done with this laststep, you are ready to proceed for
your first Android example but before that we will see few more
important concepts related to AndroidApplication Development.
