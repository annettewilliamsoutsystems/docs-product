---
tags: runtime-mobileandreactiveweb;
summary: 
---

# Rating

You can use the Rating UI Pattern to 

![](<images/rating-1-ss.png>)

**How to use the Rating UI Pattern**

1. In Service Studio, in the Toolbox, search for `Rating`.

    The Rating widget is displayed.

    ![](<images/rating-2-ss.png>)

1. From the Toolbox, drag the Rating widget into the Main Content area of your application's screen.

    ![](<images/rating-3-ss.png>)

    By default, the Rating pattern 

1. On the **Properties** tab, you can customize the Rating's look and feel by setting any of the optional properties.

    ![](<images/rating-8-ss.png>)

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| Property | Description |
|---|---|
| RatingValue (Decimal): Mandatory | The number that appears inside the badge. Set this to a data source that contains the value you want to display.  |
| RatingScale (Integer): Optional | Set rating scale to any value. The default is 5 which means the rating is from 0 to 5. |
| IsEdit (Boolean): Optional | If True,... If False, ... Allows user interaction in runtime or is "read-only".  |
| Size (Size Identifer): Optional | Allows 3 different sizes, small, medium, and base. Base is the default size.  |
| ExtendedClass (Text):Optional | Add custom style classes to the Rating UI Pattern. You define your [custom style classes](../../../look-feel/css.md) in your application using CSS. <p>Examples <ul><li>_Blank_ - No custom styles are added (default value).</li><li>_"myclass"_ - Adds the _myclass_ style to the Rating UI styles being applied.</li><li>_"myclass1" "myclass2"_ - Adds the _myclass1_ and _myclass2_ styles to the Rating UI styles being applied.</li></ul></p> |
