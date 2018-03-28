#### **Thunkable for iOS **

# Spreadsheets powered by Airtable

---

The backbone to many apps is data and managing your app data in a Spreadsheet can be very user friendly. The Spreadsheet component is powered by Airtable, a radically different and Ashton Kutcher's favorite way of organizing anything from film projects to apartment hunts and customer lists.

Airtable looks like a spreadsheet but actually acts like a database so it can store attachments i.e. images in your spreadsheets \(and not just text\) and easily link records between spreadsheets

* [Set up](#set-up)
* [Getting, uploading, updating and deleting data in a spreadsheet](#getting-uploading-updating-and-deleting-data-in-a-spreadsheet)

---

### Set up

#### Step ① / Create your [free Airtable](https://airtable.com/) spreadsheet and account![](/assets/spreadsheet-airtable-✕-fig-1.png)![](/assets/spreadsheet-airtable-✕-fig-2.png)

#### Step ② / Connect your Airtable spreadsheet with Thunkable

There are four properties that you need to retrieve from Airtable to connect it with Thunkable: `API key`, `Base ID`, `Table Name` and `View Name`

![](/assets/spreadsheet-airtable-✕-fig-3.png)

`API key`

To retrieve the API key, you'll have to navigate to the Account page and generate an API Key

![](/assets/spreadsheet-airtable-✕-fig-4.png)![](/assets/spreadsheet-airtable-✕-fig-5.png)![](/assets/spreadsheet-airtable-✕-fig-6.png)

`Base ID`

To retrieve the Base ID, you'll actually have go to the [Airtable API documentation](https://airtable.com/api) page and select your spreadsheet. You'll then have to select the Node.js tab of the code editor and find the Base ID in the code as shown below

![](/assets/spreadsheet-airtable-✕-fig-7.png)![](/assets/spreadsheet-airtable-✕-fig-8.png)

`Table Name` and `View Name`

The Table Name and View Name can be retrieved by grabbing the fields from your spreadsheet as shown below

![](/assets/spreadsheet-airtable-✕-fig-9.png)

---

### Getting, uploading, updating and deleting data in a spreadsheet

#### Setting items for a ListView from an Airtable column

![](/assets/spreadsheet-airtable-✕-fig-10.png)

#### ![](/assets/spreadsheet-airtable-✕-fig-11.png)![](/assets/spreadsheet-airtable-✕-fig-12.png)Getting data

| Event | Description |
| :--- | :--- |
| Get Cell \(`rowNum`, `columnName`\) | Returns the `value` of a specific cell |
| Get Column \(`columnName`, `maxNumRows`\) | Returns a `column` as a list  |
| Get Row \(`rowNum`\) | Returns a `row` as an object |
| Get All Rows  |  |
| Get Selected Rows \(`startingRowNumber`, `numRows`\) |  |

---

#### Uploading and updating data

You can only upload data as a new row \(and not as a new column\)

| Event | Description |
| :--- | :--- |
| Create Row \(`rowObject`\) | If successful, creates a new `row` of data |
| Set Cell \(`rowNum`,`columnName`,`value`\) | Updates the `value `of a cell in a particular `rowNum` and `columnName` |
| Update Row \(`rowNum`\) |  |
| Update Row Num \(`rowNum`, `rowObject`\) |   |
| Replace Row \(`rowNum`\) |   |
| Replace Row Num \(`rowNum`, `rowObject`\) |  |

---

#### Deleting data

| Event | Description |
| :--- | :--- |
| Delete Row \(`rowNum`\) |  |
| Delete Row Num \(`rowNum`, `rowObject`\) |  |



