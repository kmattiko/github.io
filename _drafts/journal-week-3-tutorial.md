***How to use the CSS Box Model to make it look right!***

CSS can be a very useful tool in adjusting the layout of your webpage. However, using CSS correctly can be a little tricky. Once you get beyond the fun of using colors, fonts, and icons you probably will want to think about how your elements are positioned on the page. Box-model is a nice way in which modern CSS can help you to add this structure to your elements.  

We will be exploring how contain, padding, border, and margin can help you to make each individual elemtns look good. It also will help you to make different parts of your page work correctly together. Really, the possiblies are endless. By correctly learning how to use the Box Model you will have a powerful tool in your toolbox. 

For example, you may want to have a page with a heading at the top of the page, an image to the right of the page, a paragraph that wraps around the image, and a list of information toward the bottom of the page. Without CSS, all of these elements will just list out from top to bottom. By correctly formatting these elements though, we can get the layout we so desired. 

I also included a short dialog of considerations to be made when selecting your size-measurements in box-sizing, and how these can relate to different screens. 

Below I will define some of the layout basics and define some option, you the user, have to rearrange your page. 

**Content**

Content refers the actual text or image that lives within the box. This often contains text, it can be a variety of elements. It might be paragraph, a title, a image, or even blank space (although this can be tricky to code.)

Either content will be driven by what is pulled from HTML like this...

```
<h1>Brain</h1>
<p>"The same thing we do every night, Pinky. Try to take over the world"</p>
```

We could then use CSS to change the style of this text content. We might want to center it for example. 

```
h1 p {
text-align: center;
}
```
It would end up looking something like this...

```
                                Brain
                "The same thing we do every night, Pinky.
                      Try to take over the world"
```

***Padding***

Padding is the space in the box module that lives directly around the context. It also lives within the border, which is listed below. Padding can be white-space (blank). But if it's child element, content, is stylized it will take on the style connected to the content. An easy example of this might be background color. 

If we took the example about from **Pinky and the Brain** and then applied a padding border like so...

```
h1 p {
text-align: center;
padding-top: 10px;
padding-right: 5px;
padding bottom: 10px;
padding-left: 5px;
}
```

This would give us some padding that is thicker on the top and top and thinner around both sides. If you wanted a shorter version of the code above to save yourself some typing you can use some shorthand. If you start by identifying that wanted padding by simply typing "padding" you could put the sizes in order from Top, Right, Bottom, and Left. Note that no commas or additional syntax is needed using this shortnahnd. The below exmple would give us the same results as what is listed above, but without the hand-cramp. 

```
h1 p {
text-align: center;
padding: 10px 5px 10px 5px;
}
```
```


***border***

***Margin***

***Size Considerations***
