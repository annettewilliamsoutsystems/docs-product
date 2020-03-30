---
tags: runtime-mobileandreactiveweb;  
summary: 
---

# Columns 

You can use the Columns UI pattern to split content into multiple columns. Additionally, you can configure the columns' behavior and define how they display on different devices. Splitting content into columns improves how information is displayed and enhances the overall user experience.

<!---You can split the columns as follows:

![](images/Column_Gutter.png)

![](images/Column_columns.png)--->

## How to Use the Columns UI Pattern

1. In Service Studio, select the **Interface** tab.

1. On the left side of the screen, in the **Search** field, enter **Columns**. 
    
    The various Column blocks are displayed. 

     ![](<images/columns-image-1.png>)

1. From the Toolbox, drag the relevant Columns block onto your application's screen. 

1. On the **Properties** tab, configure the column behavior to define how the columns will display on different devices.

After following these steps and publishing the module, you can test the pattern in your app.

For an uneven number of columns, the following splits apply:

**Entities.ColumnBreak.BreakNone (default)**

![](images/Column_break_none.png)  

**Entities.ColumnBreak.BreakMiddle**

![](images/Column_break_middle.png)

**Entities.ColumnBreak.BreakLast**

![](images/Column_break_last.png)

**Entities.ColumnBreak.BreakFirst**

![](images/Column_break_first.png)

## Properties

**Property** |  **Description** |  **Default Value**  
---|---|---  
![](images/input.png) UseGutter  |  Creates a space between columns.  | True  
![](images/input.png) PhonePortraitBreak  |  Behavior of the columns on a phone with portrait orientation.  |  BreakNone  
![](images/input.png) PhoneLandscapeBreak  |  Behavior of the columns on a phone with landscape orientation.  |  BreakNone  
![](images/input.png) TabletPortraitBreak  |  Behavior of the columns on a tablet with portrait orientation.  |  BreakNone  
![](images/input.png) TabletLandscapeBreak  |  Behavior of the columns on a tablet with landscape orientation.  |  BreakNone  
  
## Samples

See how the [Account Dashboard sample](https://silkui.outsystems.com/Samples_Mobile.aspx#Mobile_Details-Samples_AccountDashboard) uses the Columns pattern:

![](images/Sample_Account_Dashboard.png)

## See Also

* OutSystems UI Live Style Guide: [Columns](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Columns6.aspx)
* OutSystems UI Pattern Page: [Columns](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=25)

