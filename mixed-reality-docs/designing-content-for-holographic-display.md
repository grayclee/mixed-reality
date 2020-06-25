---
title: Designing content for holographic display
description: Design guidelines and best practices for holographic display
author: yoonpark
ms.author: dongpark
ms.date: 06/18/2020
ms.topic: article
keywords: design, holographic display, content design
---
# Designing content for holographic display

![Ulnar side hand location](images/UX/UX_Hero_HandMenu.jpg)

When designing content for holographic display, there are several elements that you need to consider to achieve the best experience. Below are some of the recommendations. To learn about the characteristics of the holographic display, see [Color, light and materials](color,-light-and-materials.md) page.

<br>

## Use dark colors on the UI's backplate
Based on our user research and testings on various types of HoloLens experiences, we found that using bright colors on the large area can cause several issues:

**1. Eye fatigue** 
Since holographic display is additive, bright color uses more light to display holograms. Bright, solid color on the large area can easily make the user's eyes fatigue. 
Do: Use dark theme on your UI and content elements if possible.
Don't: Use white or bright solid color

[TODO: Image - large area with strong white color]

**2. Hand occlusion** 
Bright color makes the user difficult to see their hands when directly interacting with objects. Since user cannot see their hands, it becomes difficult to perceive the depth/distance between the hand/finger to the target surface. Finger Cursor compensates this issue but still challenging on bright white surface.

[TODO: Image - Dark & Bright theme with hand interactions]

**3. Color uniformity**
Because of the characteristics of holographic displays made with lights and mirrors, a large bright area can become blotchy. 

[TODO: Image - prominent white window vs dark window through hololens display]

## Use semibold or bold font family

HoloLens has display that can render content at 47 PPD(Pixels Per Degree). This allows your experience show beautiful high-resolution text. However, it is recommended to avoid thin font families such as light or semilight because the vertical strokes can jitter in small font size.  

[TODO: Image - light vs semibold font example]


## Use transparent or translucent UI backplate sparsely

- Performance
- DepthLSR issue
- Visual complexity, accessibility

[TODO: Image - plated vs unplated]






---

## Hand menu in MRTK (Mixed Reality Toolkit) for Unity
**[MRTK](https://github.com/Microsoft/MixedRealityToolkit-Unity)** provides scripts and example scenes for the hand menu. HandConstraintPalmUp solver script allows you easily attach any objects to the hands with various configurable options.

* [MRTK - Hand Menu with HandConstraint and HandConstraintPalmUp
](https://github.com/microsoft/MixedRealityToolkit-Unity/blob/mrtk_release/Documentation/README_Solver.md#hand-menu-with-handconstraint-and-handconstraintpalmup)


<br>

---


## See also

* [Cursors](cursors.md)
* [Hand ray](point-and-commit.md)
* [Button](button.md)
* [Interactable object](interactable-object.md)
* [Bounding box and App bar](app-bar-and-bounding-box.md)
* [Manipulation](direct-manipulation.md)
* [Hand menu](hand-menu.md)
* [Near menu](near-menu.md)
* [Object collection](object-collection.md)
* [Voice command](voice-input.md)
* [Keyboard](keyboard.md)
* [Tooltip](tooltip.md)
* [Slate](slate.md)
* [Slider](slider.md)
* [Shader](shader.md)
* [Billboarding and tag-along](billboarding-and-tag-along.md)
* [Displaying progress](progress.md)
* [Surface magnetism](surface-magnetism.md)
