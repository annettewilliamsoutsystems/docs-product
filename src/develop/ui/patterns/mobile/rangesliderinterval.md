---
tags: runtime-mobileandreactiveweb;  
summary: 
---

# Range Slider Interval 

You can use the Range Slider Interval pattern to set an interval by dragging two handles. You can control an interval value with simple and interactive user inputs.

## How to Use the Range Slider Interval UI Pattern

1. In Service Studio, in the Toolbox, search for  `Range Slider`. 

    The Range Slider widget is displayed.

    ![](images/rangeslider-widget.png)

1. From the Toolbox, drag the Range Slider widget onto your application's screen.
1. Bind your variables to the InitialIntervalStart and InitialIntervalEnd inputs and use the OnChange event to add your logic to handle value changes.

    ![](images/range_slider_interval_interaction.png)  

1. After setting the MinValue, MaxValue, InitialIntervalStart and the InitialIntervalEnd, create the OnChange event.

    ![](images/range_slider_interval_create.png)  

1. Create an integer value and assign it.

    ![](images/range_slider_interval_assign.png)  

**Result**:

![](images/RangesliderInterval_BasicEndResult.gif)

### Changing the Color of the Bar

![](images/range_slider_interval_change_colors.png)

![](images/range_slider_interval_change_color_of_the_bar.png)

![](images/range_slider_interval_change_colors_2.png)

### Changing the Size of the Handles

![](images/change_size_of_handles.png)

![](images/change_size.png)

![](images/change_size_of_handles_2.png)

## Properties

**Input Name** |  **Description** |  **Default Value**  
---|---|---  
![](images/input.png) |  MinValue  |  Slider's minimum value.  |  none  
![](images/input.png) |  MaxValue  |  Slider's maximum value.  |  none  
![](images/input.png) |  InitialIntervalStart  |  Value selected by default. Must be between min and max values.  |  none  
![](images/input.png) |  InitialIntervalEnd  |  Default value for the interval's end. Must be between min and max values.  |  none  
![](images/input.png) |  Step  |  Slider moves in increments of Step. If Step is 10, the slider will go from 0 to 10, to 20, to 30, etc.  |  1  
![](images/input.png) |  ShowPips  |  Show pips below the slider.  |  _True_  
![](images/input.png) |  PipsStep  |  Range interval after which a Pip is drawn (when ShowPips is enabled). If not specified, the component will try to guess what step fits your data.  |  -1  
![](images/input.png) |  ChangeEventDuringSlide  |  Trigger Change events while the slider is being dragged. If set to False, the Change events will only be triggered when the user releases the slider.  **Tip**: if you're refreshing a query based on the value of the slider, you probably want to set this to False.  |  _True_  
  
  
## Samples

The following example uses the Range Slider Interval pattern:

![](images/RangeSliderInterval-Sample-1.PNG)

## See Also

* OutSystems UI Live Style Guide: [Range Slider Interval](https://outsystemsui.outsystems.com/WebStyleGuidePreview/RangeSliderInterval.aspx)
* OutSystems UI Pattern Page: [Range Slider Interval](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=61)