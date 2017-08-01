#### **Thunkable for Android **❤

# Activity Starter ![](/assets/activity-starter-icon.png)

---

The Activity Starter component lets you combine applications by having one application start up other applications.

To start an application with the Activity Starter, you must supply certain control information to the Android operating system. You do this by setting various properties of Activity Starter before calling the ActivityStarter.StartActivity method.This section gives some examples.

The sample app uses the Activity Starter to open the Facebook and Instagram app if it's installed on a user's device

---

#### Open a deep link to an installed app

The Activity Starter can only open another app if it's installed on a user's device

| Activity to Start | Action | Activity Class | Activity Package | DataURI | DataURI Example |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Send an email from your default app | android.intent.action.VIEW |  |  | mailto:{emailAddress} | mailto:hello@thunkable.com |
| Open Facebook app to a specific page | android.intent.action.VIEW |  |  | fb://facewebmodal/f?href={webUrl} | fb://facewebmodal/f?href=[https://www.facebook.com/thunkable](https://www.facebook.com/thunkable) |
| Open Instagram app to a specific page | android.intent.action.VIEW | com.instagram.android.activity.UrlHandlerActivity | com.instagram.android | [http://instagram.com/\_u/{instagramHandle}](http://instagram.com/_u/{instagramHandle}) | [http://instagram.com/\_u/thunkable](http://instagram.com/_u/thunkable) |
| Open a link in an external web browser | android.intent.action.VIEW |  |  | https://thunkable.com |  |
| Open an app made on Thunkable | com.thunkable.android.{username}.{appname} | com.thunkable.android.{username}.{appname}.Screen1 |  |  |  |

---

#### Open Facebook deep link in app if app is installed, open in website if not

![](/assets/activity-starter-blocks-1.png)

