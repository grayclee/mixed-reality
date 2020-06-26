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

Bright color makes the user difficult to see their hands when directly interacting with objects. Since the user cannot see their hands, it becomes difficult to perceive the depth/distance between the hand/finger to the target surface. Finger Cursor compensates for this issue but still challenging on a bright white surface.

[TODO: Image - Dark & Bright theme with hand interactions]

**3. Color uniformity**

Because of the characteristics of holographic displays, a large bright area can become blotchy. 

[TODO: Image - prominent white window vs dark window through hololens display]

## Use semibold or bold font family

HoloLens has a display that can render content at 47 PPD(Pixels Per Degree). This allows your experience to show beautiful high-resolution text. However, it is recommended to avoid thin font families such as light or semi-light because the vertical strokes can jitter in small font size.

[TODO: Image - light vs semibold font example]


## Use transparent or translucent UI backplate sparsely
[TODO: Image - plated vs unplated]

**1. Performance**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae quam efficitur, tristique nunc eu, aliquam felis. Vivamus faucibus elit sollicitudin sem tincidunt placerat. Integer at varius metus. Etiam imperdiet rhoncus leo ut lobortis. Praesent aliquam ligula a urna sodales, eu tempus nisl sodales. 

**2. DepthLSR issue**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae quam efficitur, tristique nunc eu, aliquam felis. Vivamus faucibus elit sollicitudin sem tincidunt placerat. Integer at varius metus. Etiam imperdiet rhoncus leo ut lobortis. Praesent aliquam ligula a urna sodales, eu tempus nisl sodales. 

**3. Visual complexity, accessibility**
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi vitae quam efficitur, tristique nunc eu, aliquam felis. Vivamus faucibus elit sollicitudin sem tincidunt placerat. Integer at varius metus. Etiam imperdiet rhoncus leo ut lobortis. Praesent aliquam ligula a urna sodales, eu tempus nisl sodales. 


---

## Dark UI examples in MRTK (Mixed Reality Toolkit) for Unity
**[MRTK](https://github.com/Microsoft/MixedRealityToolkit-Unity)** provides many UI building block examples based on the dark color schemes.

* [Near Menu](https://microsoft.github.io/MixedRealityToolkit-Unity/Documentation/README_NearMenu.html)
* [Dialog](https://microsoft.github.io/MixedRealityToolkit-Unity/Assets/MRTK/SDK/Experimental/Dialog/README_Dialog.html)
* [Hand Menu](https://microsoft.github.io/MixedRealityToolkit-Unity/Documentation/README_HandMenu.html)


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
