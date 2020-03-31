---
tags: runtime-traditionalweb; 
summary: SectionIndex organizes the content of a screen, enabling quick navigation within the page.
---

# Section Index

You can use the Section Index UI Pattern to organize the content of a screen, enabling quick navigation within the page.

**How to use the Section Index UI Pattern**

**Prerequisite**: Your application screen contains sections.

1. In Service Studio, in the Toolbox, search for `Section Index`. 

    The Section Index widget is displayed.

    ![](<images/sectionindex-image-6.png>)

1. From the Toolbox, drag the Section Index widget onto your application’s screen.

     A link is automatically created to every section you have on the screen. The name of the link is based on the text you entered in the Title placeholder of each section.

    ![](<images/sectionindex-image-2.png>)
   
After following these steps and publishing the module, you can test the pattern in your app.

## Properties

| **Property** |  **Description** |  **Usage** | 
|---|---|---|
| IsSmooth (Boolean): Optional  |  If IsSmooth is True, the navigation to the destination is animated. If set to false, navigation is instant. |
| IsFixed (Text): Optional  |  If Fixed is true, the Section Index is always in the same position on the screen. If Fixed is false, it scrolls with the page content. |
| TopPosition (Integer): Optional  |  Distance in pixels from the top of the page to the first item in the section index.  |
| ExtendedClass (Text): Optional |  Add custom style classes to the block. |
  


## Additional notes

Remember to use the **Title** placeholder in the Section Index pattern as this defines the text for each SectionIndex link. 

## Device compatibility

In Internet Explorer, `position: fixed` is used instead of `position sticky` as the latter is unsupported.

## Compatibility with other patterns

This UI pattern only works with the Section Pattern in the same screen.

## See also
* OutSystems UI Live Style Guide: [Section index](https://outsystemsui.outsystems.com/WebStyleGuidePreview/SectionIndex.aspx)
* OutSystems UI Pattern Page: [Section Index](https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternDetail?PatternId=65)

