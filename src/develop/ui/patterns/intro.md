---
summary: Drag and drop patterns to use the most common UI components, like calendar, tool tip, carousel, and many more.
---

# Patterns

<div class="info" markdown="1">

For the list of patterns and their previews, check out the <a href="https://outsystemsui.outsystems.com/OutSystemsUIWebsite/PatternOverview" title="Demos and previews of the patterns">UI Patterns</a> on the OutSystems UI website .

</div>

In OutSystems, you can use the pre-built patterns, which implement common UI patterns and components. Patterns cover the most used UI patterns and interactions in mobile and web apps, allowing developers to distance themselves as much a possible from the need to program CSS.

## Customization 

You can customize the patterns by writing additional CSS that changes their look and feel. Additionally, you can change the structure to display something else or remove unwanted elements. You can even change the code and the pattern behavior, such as adding swipe gestures or adding new events. Keep in mind that code customizations can make patterns behave unpredictably and aren't officially supported.

By creating additional [CSS](../look-feel/css.md) on a new module, it's possible to override the look of most patterns.

Changing the structure of a pattern by, for instance, adding a couple of tabs, requires the pattern to be copied to a new eSpace and then adding the correct placeholders. The same rule applies to code changes. A copied pattern isn't upgraded with OutSystems UI versions that have code fixes.

**Note:** From OutSystems 10 onward, it's not possible to directly change modules that are part of the UI framework. If you need to change a specific pattern, copy it and make the necessary changes in your cloned version.

