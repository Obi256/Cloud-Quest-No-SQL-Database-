# Cloud-Quest-No-SQL-Database-
In this project we will be creating s No SQL database tohelp behaiviors from metadata, such as movies wanted and device types.

### Prerequisites
Access to the AWS console, Dynamo DB, Github Account (for documentation) 

## Step 1:  open the Aws Console, navigate to the Dynomo DB service

Cretae a new table 

In the table details give a table name

type a partition key and choose a string

For short key input "LastDateWatched" 

In the Settings Section keep everything default

##  Step 2: Create Table  

In the tables section, review the status of the table, make sure it is active

Click the table name 

In the navigation pane click update settings 

Choose the radio button to select 

## Step 3: Click actions and choose create item

In the attributes section the clck username and then type the sort key

Add another Attribute and click string

Add the attribute name VideoID, and then type the value of the string

For attribute name, type performed languge, for value type english

Click add new attribute, choose list, then for attribute name type "SuppourtedDeviceTypes"

## Step 4: click insert a field to expand dropdown, then choose string.

For attribute name click the ( + ), then for value in the new text box type "Amazon Fire TV"

For value Insert field then choose string 

For Value, in the new text box type "Amazon Fire Tablet" then create item 

## Step 5: In the left pane click explore items

In the items returned sections, under userID click the following string

Click add new attribute, then choose a number

For attribute name, type "LastStopTime" for value type 90

Click save and close

Expand Query section, click scan/ query items

Click query tab then use UserID for partiton key, type the value

On the dropdown menu choose greater than, In right text box type value 

Click Run

## Step 6: Review the items returned

To change Query criteria for UserID type the value
