#### **Thunkable for Android **❤

# Floating Action Button \(FAB\) ![](/assets/FAB-icon.png)

---

Floating Action Buttons are circular Material Design standard buttons that represent the primary action in an app. Unlike regular buttons, FABs float above the other elements on the screen. Material Design FABs can be standard sized \(56 x 56 dp\) or mini \(40 x 40 dp\) and can be customized both in terms of color and the icon on the button.

Note: The Floating Action Button is not yet visible on the Phone Previewer when you add it to your app. It is visible during Live Testing and when you Export your app.

* [Position your FAB](#position-your-fab)
* [Select your icon](#select-your-icon)
* [Style the FAB](#style-the-fab)
* [Add animation to your FAB](#add-animation-to-your-fab)

![](/assets/Thunkable_Walkie.gif)

---

#### Position your FAB

The most common position for FAB is on the bottom right with a padding of 16 or 24 dp from the bottom and right. There is also an alternate use case as specified by Material Design standards. We recommend sticking to these guidelines in most cases since users are familiar with these positions and will more likely engage in the primary action of your app.![](/assets/fab-fig-1.png)

---

#### Select your icon

For user's convenience, Thunkable has automatically preloaded the Material Icon Font into the FAB and you can select from the entire library the 'Icon Name'. If the name has two words e.g. mic off, you will need to add an underscore e.g. mic\_off.

To see more options, [navigate here to the library](https://material.io/icons/)

![](/assets/fab-fig-2.png)

---

#### Style the FAB

| Property | Description |
| :--- | :--- |
| Icon Name | Default \(Add\). You can choose any icon from the [Material Icon Font](https://material.io/icons/). If the name has two words e.g. mic off, you will need to add an underscore e.g. mic\_off. |
| Icon Color | Default \(White\). You can choose any color on the Designer palette or customize the color to any RGB value in the Blocks edito |
| Background Color | Default \(Blue\). You can choose any color on the Designer palette or customize the color to any RGB value in the Blocks editor |
| Padding Bottom \(dp\) | Margin from bottom edge of phone in dp, or device-independent pixels. For bottom-right FABs, we recommend a bottom padding of 24 dp |
| Padding Right \(dp\) | Margin from right edge of phone in dp, or device-independent pixels. For bottom-right FABs, we recommend a right padding of 24 dp |
| Button Size | Default \(Standard 56 x 56 dp\) or mini \(40 x 40 dp\) which are good as secondary buttons from a standard FAB. |
| Animation Duration \(milliseconds\) | Applies only to instances where you change the FAB Icon Name and specifies the duration of the fade animation when switching between the icons. |
| Visible | If checked, the button will be visible on the screen |

---

#### Add animation to your FAB

Since FABs often represent the primary action in an app, developers will often add animation to transition between FABs depending different events that have been triggered

![](/assets/fab-fig-3.png)



| Event | Description |
| :--- | :--- |
| Click | User tapped and releases the button |



