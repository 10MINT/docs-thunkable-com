#### **Thunkable for iOS **

# Realtime DB powered by Firebase ![](/assets/firebase-ios-icon.png)

---

Realtime DB powered by Firebase is cloud storage component that stores and retrieves `keys` and their corresponding `values` in a database that can be accessed in real-time \(super fast\). 

This version of the component supports storing app data in unique project buckets associated with a user's project. A future version will include the option for users to save their data to their own unique Firebase instance.

---

#### Save Data to Firebase

![](/assets/firebase-ios-fig-1.png)

---

#### Update Data in Realtime

![](/assets/firebase-ios-fig-2.png)

---

#### Save, Retrieve & Update Data in Realtime

| Event | Description |
| :--- | :--- |
| Save \(`key`, `value`\) | Asks Firebase to save a given `value` under the given `key` |
| Get \(`key`, `value`\) | Asks Firebase to get the `value` stored under the given `key` |
| Add Listener \(`key`\) | Asks Firebase to listen to a specific `key` for changes in the database. Required for Data Changed block. |
| Data Changed \(`key`, `value`\) | Asks Firebase for updates to `value` for specified `key`. Requires an Add Listener block. |
| Remove Listener \(`key`\) | Ask Firebase to stop listening to a specific `key` for changes in the database |



