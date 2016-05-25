# adapt-componentSlider

**Component Slider** is a xtreem *presentation component*.

The extension changes the presentation of a component from being vertically stacked to horizontally ordered. This is achieved by implementing a left and right or tabbing navigational element to the article. By default, the **Component Slider** is available on large resolutions only (medium and small resolutions can be added but are currently unsupported). When viewing at other resolutions the blocks return to being vertically stacked.

##Installation

Open the */src/components* folder in a new terminal window on Mac OSX or right click the folder and select 'Git Bash Here' on Windows.

Git clone the component, making sure to delete the hidden **.git** folder from the *adapt-componentSlider* folder.

##Settings  

The attributes listed below are used in *articles.json* to configure **Component Slider**, and are properly formatted as JSON in [*example.json*](https://github.com/xtreem/adapt-componentSlider/blob/master/example.json).

**_componentSlider** (object): The Component Slider object that contains values for **_isEnabled**, **_slideAnimationDuration**, **_heightAnimationDuration**, **_isEnabledOnScreenSizes**, **_hasTabs**, **_hasArrows**, **_startIndex**, **_hasUniformHeight**, and **_minHeight**.

>**_isEnabled** (boolean): Turns Component Slider on and off. Acceptable values are true and false.

>**_slideAnimationDuration** (number): Sets the slide duration, in milliseconds, of the animation between blocks.

>**_heightAnimationDuration** (number): Sets the duration, in milliseconds, of the animation between varying blocks heights.

>**_isEnabledOnScreenSizes** (string): Defines which screen sizes the Component Slider displays the navigation elements on. Acceptable values are large, medium and small.

>**_hasTabs** (boolean): Turns the tab navigation on and off. If *_hasTabs* is set to true, you must set *_hasArrows* to false. Acceptable values are true and false. 

>**_hasArrows** (boolean): Turns the arrow navigation on and off. If *_hasArrows* is set to true, you must set *_hasTabs* to false. Acceptable values are true and false. 

>**_startIndex** (number): Sets which block displays on page load.

>**_hasUniformHeight** (boolean): Sets all elements within the Component Slider to use the highest blocks height. Acceptable values are true and false.

>**_minHeight** (number): Sets a minimum height on the *.article-block-slider* container class.

## Limitations
 
Only one navigation element (Arrows or Tabs) should be active at any one time.  

The **Component Slider** and **Quicknav** extensions don't interact well together when the **Component Slider** is the last component on a page with an enabled **Quicknav.**  

----------------------------
**Version number:**  2.0  
**Framework versions:**  2.0  
**Author / maintainer:** xtreem  
**Accessibility support:** WAI AA  
**RTL support:** No  
**Cross-platform coverage:** To be confirmed  
