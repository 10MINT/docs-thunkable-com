#### **Thunkable for Android **❤

# Troubleshooting

---

### `Live Testing`

If your app does not appear on your device, the most likely problems are:

* You may have images or other media assets that are too large to send over in real-time
* You may have an outdated version of the Thunkable app. Download the latest Thunkable live development app for Thunkable from above.
* Your device may not be connected to wifi. Make sure you see an IP address at the bottom of the Thunkable App screen on your phone or tablet.
* Your device may not be connected to the same wifi network as your computer. Make sure both devices are connected to the same wifi network name.
* Try using a different browser. If you are on Chrome, you can also try opening Thunkable a New Incognito Window

---

### `Building Apps for Downloading / Publishing`

If your app does not build, install or frequently crashes, the most likely problems are:

* [Extensions](/Android/extensions.md)

  * Extensions are created by the community and many of them work wonderfully on Thunkable.  A few of them do lead to more frequent app crashes

* Images

  * App icon too large \(we recommend 96 px by 96 px\)
  * Too many / too large images \(the app size limit is 10MB\)
  * Some users have detected that Thunkable works better with .pngs than .jpgs

* Too many screens \(there is not a hard limit on 10 screens but performance reduces beyond that\)

* Blocks

  * Errors in blocks \(usually this will prevent the app from building\)
  * Too many blocks \(we have seen a few cases where a lot of blocks create performance issues\)

---

### `Backpack`

If you are trying to empty your backpack:

* Emptying the backpack can be completed with a right click on the Blocks Editor![](/assets/empty-backpack.png)

---

### `Tablet`

If you cannot see the Tablet previewer:

* Need to set Screen Size to 'Responsive' and check to see preview on Tablet size![](/assets/tablet-screen-fig-1.png)

---

### `AdMob` ![](/assets/admob-icon.png)

If your ads are not showing up:

* AdMob account created very recently. Usually it takes at least a few hours for the account to be activated
* For Banner Ads, Screen set to 'Fixed'. Screen needs to be set to 'Responsive'
* Load Ad block not called in Blocks Editor
* Account has been suspended by AdMob. Clicking ads on your own app can lead to suspensions as can one or more users repeatedly clicking the ads on your app. Accounts can also be suspended for deceptive ad placement that generates accidental clicks
* [Check the AdMob forum for more potential errors](https://community.thunkable.com/c/professional/admob)

---

### `Image` ![](/assets/image-icon.png)

If you're images are not showing up in app or in live preview

* We have seen users with better performance using .pngs vs. .jpgs



