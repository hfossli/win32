---
Description: 'When you draw a line, you must pass the address of a Pen object to the DrawLine method of the Graphics class.'
ms.assetid: '4524908f-f9c2-4807-b045-eb9e43a6668b'
title: Drawing Opaque and Semitransparent Lines
---

# Drawing Opaque and Semitransparent Lines

When you draw a line, you must pass the address of a [**Pen**](-gdiplus-class-pen-class.md) object to the [DrawLine](-gdiplus-class-graphics-drawline-methods.md) method of the [**Graphics**](-gdiplus-class-graphics-class.md) class. One of the parameters of the **Pen** constructor is a [**Color**](-gdiplus-class-color-class.md) object. To draw an opaque line, set the alpha component of the color to 255. To draw a semitransparent line, set the alpha component to any value from 1 through 254.

When you draw a semitransparent line over a background, the color of the line is blended with the colors of the background. The alpha component specifies how the line and background colors are mixed; alpha values near 0 place more weight on the background colors, and alpha values near 255 place more weigh on the line color.

The following example draws an image and then draws three lines that use the image as a background. The first line uses an alpha component of 255, so it is opaque. The second and third lines use an alpha component of 128, so they are semitransparent; you can see the background image through the lines. The call to [**Graphics::SetCompositingQuality**](-gdiplus-class-graphics-setcompositingquality-compositingquality-.md) causes the blending for the third line to be done in conjunction with gamma correction.


```
Image image(L"Texture1.jpg");
graphics.DrawImage(&amp;image, 10, 5, image.GetWidth(), image.GetHeight());
Pen opaquePen(Color(255, 0, 0, 255), 15);
Pen semiTransPen(Color(128, 0, 0, 255), 15);
graphics.DrawLine(&amp;opaquePen, 0, 20, 100, 20);
graphics.DrawLine(&amp;semiTransPen, 0, 40, 100, 40);
graphics.SetCompositingQuality(CompositingQualityGammaCorrected);
graphics.DrawLine(&amp;semiTransPen, 0, 60, 100, 60);
```



The following illustration shows the output of the preceding code.

![illustration showing an image overlaid by three wide lines: one opaque, one slightly transparent, and one very transparent](images/compqualline.png)

 

 


