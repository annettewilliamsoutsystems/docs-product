---
tags: runtime-traditionalweb; 
summary: Counter shows the total number of occurrences of several values regarding a single topic.
---

# Counter

You can use the Counter UI Pattern to display numerical information as a notification. The Counter UI pattern is frequently used to notify users about new messages or tasks.  

![](<images/counter-image-5.png>)

**How to use the Counter UI Pattern**

1. In Service Studio, in the Toolbox, search for `Counter`. 

    The Counter widget is displayed.

    ![](<images/counter-image-7.png>)

1. From the Toolbox, drag the Counter widget into the Main Content area of your application's screen.

    ![](<images/counter-image-8.png>)

1. On the **Properties** tab, you can customize the Counter's look and feel by setting any of the optional properties, for example, the height and orientation.

    ![](<images/counter-image-3.png>)

    
1. Additionally, you can customize the Counter's number, text, and icon from the **Properties** tab of each of the Counter's widgets.

After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |
|---|---|
| Orientation (Orientation Identifier): Optional  | Set the counter orientation. By default the counter is displayed horizontally. <p> Examples <ul><li>_Entities.Orientation.Horizontal_ - The counter displays horizontally </li></ul> <ul><li>_Entities.Orientation.Vertical_ - The counter displays vertically</ul></li></p> |
| Height (Text): Optional  | Set the counter height. By default the counter height is 100 (pixel units). | 
| ExtendedClass (Text): Optional  |  Add custom style classes to the Counter UI Pattern. You define your custom style classes in your application using CSS. <p>Examples <ul><li>_Blank_ - No custom styles are added (default value)</li><li>_''myclass''_ - adds the _myclass_ style to the Counter UI styles being applied<li>_''myclass1'' ''myclass2''_ - adds the _myclass1_ and _myclass2_ styles to the Counter UI styles being applied</li></ul></p> | 

<!---  Added to yml file
## See also

* OutSystems UI Live Style Guide: [Counter](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Counter.aspx)
* OutSystems UI Pattern Page: [Counter](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=30)