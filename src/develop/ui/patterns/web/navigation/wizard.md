---
tags: runtime-traditionalweb; 
summary: Wizard splits complex tasks and process into steps.
---

# Wizard


**_Note:_**  _Applicable to Traditional Web Apps Only_.

You can use the Wizard UI pattern to split large complex tasks and processes into smaller manageable steps. Wizards usually include explicit button navigation to move a step forward or backward. 

**How to Use the Wizard UI Pattern**

1. In Service Studio, select the **Interface** tab.

2. On the left side of the screen, in the **Search** field, enter **Wizard**. 
    
    The Wizard block is displayed. 

     ![](<images/wizard-image-10.png>)

3. From the Toolbox, drag the Wizard block onto your application's screen.  

    ![](<images/wizard-image-1.png>)

4. Drag the required number of Wizard Items into the Content placeholder.

    ![](<images/wizard-image-11.png>)

     **Note**: Each Wizard Item represents a seperate step.

5. Set the relevant content in each of the Wizard Item placeholders.

6. Set the relevant properties for each of the steps.

    ![](<images/wizard-image-12.png>)

After following these steps and publishing the module, you can test the pattern in your app.


## Properties

### Wizard

| **Property** |  **Description** |  **Usage** | 
|---|---|---|---|---|
| Orientation (Orientation Identifier): Optional  |  Set the orientation. |
| ExtendedClass (Text): Optional  |  Add custom style classes to the block. | 

### Wizard Item

| **Property** |  **Description** |  **Usage** | 
|---|---|---|---|---|
| Step (Step Identifier): Mandatory | Set the step. |
| UseTopLabel (Boolean): Optional  |  If True, label is placed above the icon. | 
| ExtendedClass (Text): Optional |  Add custom style classes to the block. | 
  


## See Also

* OutSystems UI Live Style Guide: [Wizard](https://outsystemsui.outsystems.com/WebStyleGuidePreview/Wizard.aspx)
* OutSystems UI Pattern Page: [Wizard](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=82)

