#### **Thunkable for Android **❤

# Test your app live via an Emulator

---

There are a variety of Android emulators out there, but Thunkable works best with Genymotion. 

Here are the steps involved in installing and using Genymotion

---

### 1 /  Installing Genymotion and creating an Android Virtual Device \(AVD\) {#step-1-installing-genymotion-and-creating-an-android-virtual-device-avd}

1. Click[here](https://www.genymotion.com/account/create/)to create a Genymotion user account.

2. Download Genymotion's[user guide](https://docs.genymotion.com/Content/Home.htm)\(under the_PDF Guides_section\) and follow the_Installation_section. Then scroll down to the_Virtual Devices_section to set up an Android Virtual Device \(AVD\) \(You need not worry about other pages\).

---

### 2 / Deploying an APK file into an AVD {#step-2-deploying-an-apk-file-into-an-avd}

Once Genymotion is installed, you can use it to run packages apps \(APK files\), including apps that you have built and packaged with Thunkable. Here is an example:

1. Start an AVD in Genymotion:

   ![](https://thunkable.com/explore/img/emulator/start-avd.png)

2. Go back to Thunkable and download your app as an APK file.

   ![](https://thunkable.com/explore/img/emulator/download-thunkable-apk.png)

3. Drag and drop the APK file to the window of the running AVD. The application should launch:

   ![](https://thunkable.com/explore/img/emulator/genymotion-with-apk.png)

---

### 3 / Connecting Genymotion to Thunkable through the Thunkable App {#step-3-connecting-genymotion-to-thunkable-through-the-thunkable-app}

You can also use Genymotion in live development in Thunkable. In order to do that, the computer you are using and the Genymotion emulator must be within the same subnet in the network. In the default setting, the Genymotion emulator and the computer are on different subnets. However, you can change the default settings to get them on the same subnet by doing the following:

1. Open the VirtualBox you have installed in Step 1
2. Identify and select the virtual machine you have made for the emulator
3. In the Network setting of that emulator, select_Adapter 2_, and select_Bridge Adapter_in the_Attached to_option. Underneath that, select either Wi-Fi or Ethernet, based on how you connect to the Internet.

   ![](https://thunkable.com/explore/img/emulator/genymotion-settings.png)

4. Load the Thunkable Live apk into the emulator. You will need to manually update the app when Thunkable releases new versions of the app. You can dowload the[most recent version here](http://thunkable.com/live/Thunkable.apk).

5. Launch the Thunkable app within the emulator and connect with the Thunkable platform using the 6 digit code.
6. The project application should appear in Genymotion after 10 or 20 seconds.



