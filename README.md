Cordova on Windows - Installation Guide
=======================================

This document describes how to install Apache Cordova and the Android SDK on a
Windows machine.  
  
To develop Android applications, you need to install the Android SDK, and also
Java, if it is not already installed on your machine.  
  
For the Android SDK, you have the option to install Android Studio or just the
Android SDK tools (SDK manager).

Install Cordova
===============

The Cordova requires **node.js**. If you have already installed node, you can
skip to the next section

1. **Install Node.js**. Cordova runs on the Node.js platform, which needs to be
installed as the first step. Download installer from: <http://nodejs.org>

<img src="https://drive.google.com/uc?export=view&id=1sGL1kBoSM595kLyds7ZDMvYRCeApbXnq" width=400 heigth= 200> </div>


2. Go ahead and run the downloaded installation file. It is recommended to use
default settings. Node.js needs to be added to the PATH environment variable,
which is done by default.  



<img src="https://drive.google.com/uc?export=view&id=156hGcPrNu86qAiNV3GOzOZRZAbXQwu3L" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=120gm98j_Gc71waPkUCu9VFyLUOE1_Cq6" width=400 heigth= 200> 


<img src="https://drive.google.com/uc?export=view&id=1PNE6tXzwfHot7jDdAIO_qLr2qtfP1OTZ" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1n7D2vsLyjUaubaVlSr5uADuJf0yFh_sC" width=400 heigth= 200>  


<img src="https://drive.google.com/uc?export=view&id=18CrhBKzWs7Dp0R_V7vstk7JIHnInA8oO" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1gsbLGm-oQhYoGldqK9pgQge7eL83GKK7" width=400 heigth= 200> 


<img src="https://drive.google.com/uc?export=view&id=1lpRfnA2ADvYq63aN6ev2sYBh-UJ6l-1h" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1rniDpChZ51rVAKO8TXXqP69rmjlpFc6G" width=400 heigth= 200> 

3. To test the installation, open a command window (make sure you open a new
command window to get the updated path settings made by the Node.js
installation), and type:  

```  
node --version
```

If the version number is displayed, Node.js is installed and working!

<img src="https://drive.google.com/uc?export=view&id=12sVqnnUT6ctRoq-DWlW6SbH_NI0UEODu" width=400 heigth= 200> 

4. **Install Git**. Git is a version control system, which is used by Cordova
behind-the-scenes. Download and install from: <http://git-scm.com>. Default
settings are recommended.

<img src="https://drive.google.com/uc?export=view&id=1xN3HdytPBLN1y-yfUddcVsDnFjdH3pRx" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1f9mTuLWbqMh6pj7gCCp_LF-A0wrbU2L_" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1Jtb5kfo2Y_nqU_vV8N355lKhfz_MX5xd" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1B_5pyN0QjjXM0Lvd85ZNDdSiIKoqT-nZ" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1jTI5aZ9vyE0uhRuD2lhjE3id5XNmzbc1" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=10ZGlAUw2rSvKPiYl0DvkBhca8ldejh27" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=12eJJ8bjnlugTb_unIf_BV_ACu6KB-nqC" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1eAzaAFTrhjVSg71zXZyxLDwTPAYS8EI3" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1aDllJj2jsVnNE_C4N4F_zxGAE94w6y-9" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1WErXOTNApcGFikDhLLd2QOJJt0ioD5ie" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1m1l5XRAfSWD_iO0ZfShxc5Yi0f5vQtpK" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1i3qrTJAqOAO5Vr-xWsyMoTfSrf72_Jfa" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1GBcT7zR_M8AL_9Hr7yqGpl4b7kel013F" width=400 heigth= 200> 

5. **Install Cordova**. Cordova is installed using the Node Package Manager
(npm). Type the following in the command window to install:  

```  
npm install -g cordova
```

<img src="https://drive.google.com/uc?export=view&id=1xtFBa30LUXOOTdzcg_Tb5uf9AV4KIRQD" width=400 heigth= 200>

6. Test the Cordova install by typing: 
 
```  
cordova --version
```

If you see the version number, you have successfully installed Apache Cordova!

<img src="https://drive.google.com/uc?export=view&id=1rSz4CmF92BXRZgGBdvrkyVlcyDhk3NPs" width=400 heigth= 200>

Installing Java
===============

The Android SDK requires the Java Development Kit (JDK), version 1.7 or later,
to be installed.  
Note that the Java Runtime Environment (JRE) is not enough, you will need the
JDK.  
To verify if you already have the JDK installed, write this on the command line:

```
javac -version
```

If you do not have the JDK installed, proceed as follows:  
  
1. Download the recent version of Java SE JDK (SE = Standard Edition) from
Oracle:
[www.oracle.com/technetwork/java/javase/downloads/](http://www.oracle.com/technetwork/java/javase/downloads/).
Click the Java SE Download to see the list of downloads. Get the "Windows x86"
download if you have 32-bit Windows, and "Windows x64" if you have 64-bit
Windows. If you do not know which version you have, find out using the Control
Panel by selecting "System and Security" and then "System", where you will find
the "System type" saying if your Windows version is 32-bit or 64-bit.

<img src="https://drive.google.com/uc?export=view&id=1ZfMoAuU2ddyv2bV2IhFoJ5Vwv_a-W3So" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1D-4WBnx3ip529SI5FUdMA3uLSQK6XYaJ" width=400 heigth= 200> 

2. Go along and run the downloaded installer file. Using the default selections
should be fine, but take a note of the directory in which you install the JDK.
You will need to add this to the PATH in a later step below.

<img src="https://drive.google.com/uc?export=view&id=1d-fzQhooZhnqADiCzL1qJGfVxtdiwbwU" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1tG0C0GpxcoJduVInnVjiSDafe61Ein-l" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1Bk3YpFiL-R1ZUqjRhx-Uxg8QDCvJqbWn" width=400 heigth= 200> 

3. Next, update your path to include the JDK. Open the **Control Panel**, click
**System and Security**, click **System**, click **Change settings**, which will
open the System Properties window. Select the **Advanced** tab, then click the
**Environment Variables** button.

<img src="https://drive.google.com/uc?export=view&id=1aNcCQEwhplR62n-tqmg3VF23GDKtq2fb" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1ac7wPzQfrd1yWU5ES-2J04Qhsit_nQIM" width=400 heigth= 200>

<img src="https://drive.google.com/uc?export=view&id=1bgBdwrbXXixUatLhLaV9Mcb1gTlA9Qte" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1z-ZazBYnwHA351Yx_H2AfH9HK1uXIljG" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=13pBFwn1juGhHmFwjURsa3uwpgr_Ikkhy" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1aNcCQEwhplR62n-tqmg3VF23GDKtq2fb" width=400 heigth= 200> 

4. In the list **User variables** select **PATH** and click the Edit button. (If
there is no PATH entry in the list, click the New button to create one.)  
  
5. At the end of the field **Variable value**, add a semicolon followed by the
path to the bin directory of the JDK install. Here is an example (note that this
must be the actual path used for the install on your machine):  
```  
;C:\\Program Files\\Java\\jdk1.8.0_161\\bin
```  
An easy way to do this is to prepare the path to add in a text editor, then
paste it at the end of the input field. When done click the **OK** button.  


<img src="https://drive.google.com/uc?export=view&id=1leuupkNSOa4FxcF0y8-RNb7fBNzaV8lF" width=400 heigth= 200> 

6. Next add the **JAVA_HOME** variable if it is not present (and if it is in the
list, you may need to update its value using the Edit button). Click the **New**
button. In the field **Variable name** type:  

```  
JAVA_HOME
```

In the field Variable value enter the path to the directory where the JDK is
installed, without the semicolon and the /bin subdirectory, for example:  
C:\\Program Files\\Java\\jdk1.8.0_161  
Click the **OK** button.

<img src="https://drive.google.com/uc?export=view&id=12botbmFuQKg9KR9AF2f7SVVodrDbZbXw" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1X7rKSL4-zV1-Rc7WNgMBFJdVeoX7oxRt" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1jADpzyjOFD_nv5FGsXinOS2BbmdvXmRW" width=400 heigth= 200> 

7. Click the **OK** button again to close the Environment Variables window.  
  
8. Now you are ready to test the install. Close any open command windows, and
open a new command window and type:  
 
``` 
javac -version
```

If you see a version number you are done with the JDK install!

<img src="https://drive.google.com/uc?export=view&id=1Qec1TCVX_aXQuxwivrnpmiCv_W6sckan" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1u4i4VeaSVAT0mbCP1fnq50v_Ast_ysVA" width=400 heigth= 200> 

Install the Android Tools
=========================

To install the necessary tools to create an Android application using Cordova,
you need the tools of the Android SDK. The easiest way to install these tools is
to install Android Studio. Optionally you can install the command line tools
only. Follow these steps to install Android Studio:

1. Go to the Android Studio download page and download and install Android
Studio for your platform. (If you would wish to go for only the SDK Tools, you
can find download links to the command line tools at the end of the Android
Studio download page.)

<img src="https://drive.google.com/uc?export=view&id=1J4OKL7W5y3RWigFeTgndLQ9LRepMEen4" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=13E5LhN2SF5MuE3dEnTjDUNLJEO69gteK" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1lVkDFyjkl_fSyDZS4psj71rErU_LrJEY" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=18lylHOiZduWrahYhBBcyPS0kb068xshG" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1MsVAUkBel5O7bU_TCh9-FJ0XFHHjnQlf" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1_vdAA6k5fH6FdiL0Z2C-DNzx7Y3q_GUi" width=400 heigth= 200> 

2. Find the path of the Android SDK tools by consulting the SDK manager
documentation page. Check in your system that the files are actually there.

<img src="https://drive.google.com/uc?export=view&id=1LVMSCPwk1bReS3-rVm3vAbkut7iUmnNi" width=400 heigth= 200> 

3. Add the path of the SDK Tools (directories **tools** and **platform-tools**
to the system PATH variable. Open the **Control Panel**, click **System and
Security**, click **System**, click **Change settings**, click the **Advanced**
tab, then click the **Environment Variables** button.

<img src="https://drive.google.com/uc?export=view&id=1gl8sPIXdwZ6AB3DYYpAdLx5qBiN7o_kU" width=400 heigth= 200> <img src="https://drive.google.com/uc?export=view&id=1l2lZdbb_wWNVqpJuhvcuxZOgOqEK16Am" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1XBdMKQ8SWptqAtTTcRnUT6QAuZHkhx9W" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1s3JvO3PoguFpzytyzIUqIrq7ORL8NtgF" width=400 heigth= 200> 

<img src="https://drive.google.com/uc?export=view&id=1SrfMRnPlFCO7dyDrNO7NLqFoLSXlYmV0" width=400 heigth= 200> 

4. In the list **User variables** select **PATH** and click the **Edit** button.

5. At the end of the field **Variable value**, add a semicolon followed by the
path to the **tools** and **platform-tools** directores of the Android SDK
install. Here is an example of what to add (note that there are two paths in one
line, separated by a semicolon):  
 
``` 
;C:\\Users\\miki\\AppData\\Local\\Android\\android-sdk\\tools;C:\\Users\\miki\\AppData\\Local\\Android\\android-sdk\\platform-tools
```  
  
You can prepare the path in a text editor, copy it and paste at the end of the
input field. Click the **OK** button when done.  
Please note that the exact path may differ in the latest download of the Android
Studio/SDK. Consult the Android documentation page for the sdkmanager for
further information.

6. Next add the **ANDROID_HOME** environment variable in system settings in the
same way that the JAVA_HOME variable was added above when installing Java. Set
ANDROID_HOME to point to the root of the Android SDK folder, for example:  
  
```
C:\\Users\\miki\\AppData\\Local\\Android\\android-sdk
```

<img src="https://drive.google.com/uc?export=view&id=1sh0uiE74k03CqRuJOHBCCQl-wIRPddcr" width=400 heigth= 200> 

7. Click the **OK** button again to close the Environment Variables window.

8. Now test the install. Close any open command windows, open a new command
window and type:  

```  
adb version
```  
This should display the version of the Android Debug Bridge.

<img src="https://drive.google.com/uc?export=view&id=1CbCk22FN6ydmNs0w8pV5Rw-UwxrgnMce" width=400 heigth= 200> 

9. As the final step, you may need to get the specific Android SDK version used
by Cordova. This can be done using the SDK manager command or by using the tools
in Android Studio.

If you get stuck
================

If you get stuck, check the documentation on the respective websites for
Cordova, Java and Android. The Cordoba documentation has a platform guide for
Android.

One thing to do is inspect all the environment variables. You can do this from a
command window (note that you must open a new command window after updating the
environment variables so that updated values are available). This shows the PATH
system:

```
echo %PATH%
```

Here is how to inspect the value of JAVA_HOME:  
  
```
echo %JAVA_HOME%
```

Installing GitHub
=================

Before configuring GitHub Desktop, you must already have a GitHub account. If
you do not have a GitHub account, click here to [Signing up for a new GitHub
account](https://github.com/join?source=experiment-header-dropdowns-home)

You can follow this method to install GitHub on your computer :

1.  Visit the GitHub Desktop download page.

<img src="https://drive.google.com/uc?export=view&id=1wt2z-6f2-tPau3KGKHEdpHQCBKY5KlLL" width=400 heigth= 200> 

<https://desktop.github.com/>

2. Choose Download for Windows

3. In your computer's Downloads folder, Install GitHub file.

4. After the program has been installed, click Run.

Cloning a repository from GitHub to GitHub Desktop
==================================================

You can clone use GitHub to clone remote repositories to GitHub Desktop.

1.  Sign in to GitHub and GitHub Desktop before you start to clone.

2. On GitHub, navigate to the main page of the repository.

3. Under your repository name, click **Clone or download**.

<img src="https://drive.google.com/uc?export=view&id=1xTDDPRhxLhRU8r4OCazeNBVQioIT4nGp" width=400 heigth= 200> 

4. Click **Open in Desktop** to clone the repository and open it in GitHub
Desktop.

<img src="https://drive.google.com/uc?export=view&id=19njlSys62KZRbWHTfLKpwSKoN2f1HRZG" width=400 heigth= 200> 

5. Click **Choose...** and, using Windows Explorer, navigate to a local path
where you want to clone the repository.

<img src="https://drive.google.com/uc?export=view&id=1Ynu2ble-9mJhRZc4MzKnbqGg5muTy6hz" width=400 heigth= 200> 

6. Click **Clone.**

<img src="https://drive.google.com/uc?export=view&id=17f7nh6IRxmzDCrMkaw2svWzxhuJ5nmYM" width=400 heigth= 200> 


