# Inspect Element

Editing HTML and CSS can feel like disarming a bomb; one little change and your project goes bananas. Your greatest ally in editing is a browser tool called **Developer Tools**. It is included in **Chrome,** **Firefox, the latest version of Internet Explorer, Edge, and Safari**.

To access inspect element, simply right-click any element within the browser window and click **'Inspect'** and _voila!_ Inspect Element is a feature that displays all of the properties of the webpage you are currently viewing.

![](http://s3.amazonaws.com/General_V88/boomyeah/company_209/chapter_2135/handouts/chapter2135_2025_Inspect-tabs.PNG)

Above is a screenshot of Chrome's Inspect window. On the gray tab bar at the top, you'll see a number of options including 'elements' and 'console'. Clicking these options will display different information about the page.

The three most important tabs of the Chrome Developer Tools window are: **'console', 'elements' ('inspector' in Firefox), and 'sources' ('resources' in Safari)**. For this tutorial, we will use **Chrome** as our example, but you shouldn't have a tough time picking up the techniques with **Firefox** or **Safari** if you follow along.

## Elements Tab

For the next couple of sections, we'll be looking at ESPN.com. Since most companies change their websites frequently, keep in mind that the current ESPN website you will see if you visit it now may look different from the one we are using in the examples/video below. Regardless, the same tools and concepts can be applied.

The **elements tab** allows you to view the HTML that is being **rendered** by your **browser**. You can see all of the classes and id's given to the HTML content as well, which is a big help for debugging CSS. The picture above shows the **elements tab** of a chunk of the HTML for ESPN.com. Notice how you can see comments too!

If you click on a particular element of the HTML in the **elements** box, you will see the right-hand side of the Inspect Element window change. This part of the window displays **a ton of CSS and JavaScript information**. There is a tab on the right side called **'styles'** and it is by far the most helpful tool when working with CSS.

![](http://s3.amazonaws.com/General_V88/boomyeah/company_209/chapter_2135/handouts/chapter2135_2023_ESPNinfo.PNG)![](http://s3.amazonaws.com/General_V88/boomyeah/company_209/chapter_2135/handouts/chapter2135_2021_ESPNbox.png)

The **styles** tab shows **all of the rendered CSS for a particular element**. The screenshots above are the CSS information for the ESPN logo on their web page. The image on the **left** shows you the computed styles of the element and the stylesheet they were taken from. Scroll all the way to the bottom of the tab and you will find the image on the **right**, which should be familiar. This image is the **box model values** of the element in question. You can see the **margin, padding, border, and the dimensions of any element on the page**. What's even cooler is that you can hover over a specific part of the box in the inspect element window and the element's particular property will be **highlighted on the actual element in the browser window**. Try it! This tool is great for tweaking positioning as you can change the values in the box in Inspect Element. (These changes are only made in the browser and will not be saved to the CSS file itself.)

Looking at the picture again, notice how there is an area that says **'element.style'**. Well, you can actually write your own CSS styling right there to manipulate the display of the web page. Of course, these changes aren't permanent, but you can imagine the usefulness of such a tool! One more thing you can do with all of the styling rules listed in the **styles** tab is to turn off the associated CSS property by unchecking a particular style item.

## How Can Inspect Element Be Used

### Great, now what?

Any web developer worth his or her salt will tell you that **Inspect Element** is a priceless tool in the fight against bad code. There are people whose jobs are to strictly make these development tools, so you are in good hands! Inspect is super easy to pick up once you've explored it a bit.  Start using it regularly and it will save you a lot of time!

# Color Picker

Color palette selection and design are important parts of designing a web page. To help with precise color selection, there are a variety of tools available to both find/define colors and assemble color palettes. Tools for generating color schemes are easily found searching the internet, but getting the exact color used on your favorite website's button borders might seem more difficult. In this section, we will outline how to use the Chrome Dev Tool's Color picker to help us find colors from other websites that we may be after!

To access the colorpicker tool, we need to first open the Chrome Dev tools and select an element with a background color. Once we have the dev tools opened and an element with a background color selected we can click on the color patch in the Style window of the Dev tools. At this point, the dev tools will display a variety of color information about the background color of the element- showing different adjustable slides, color code values, related colors, and a gradient of different intensities and darkness.

To use the color picker to find the values of colors on the page, click the eye dropper icon to toggle color-picker to ON (should turn blue). At this point, you can move your mouse cursor over the webpage and a small circle showing the magnified pixels near your cursor will be displayed, with the central pixel outlined and its' color value displayed on click.

![COLORPICKERWHYYOULEAVEME! :(](https://s3.amazonaws.com/General_V88/boomyeah2015/codingdojo/curriculum/content/chapter/colorpicker2.png)

#### NEXT: [The Display Property](./display_property.md)
