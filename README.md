# Tutorials Curated

This repository consists of the tutorials and tasks encountered while learning the fundamentals of web development, and fullstack.

Further it alos consists of some fundamental concepts and important points to be looked into for a satisfactory understandinng of web develoment.

<br />
<br />

## CSS

The basic sytaxes and elements used for styling in css are described below.

<br />

### **CSS basics**

<br />
<br />

### **CSS Box Model**

**Important syntax parameters included for styling box models in css.**

- Padding 
- Border
- Margin
- Box-sizing 
    - Border-box: Makes the height and box account for the padding and border of the element.<br />That is the height and width given are used as the height and with of the box, and the border and padding fit into it.

**Note on Padding:**
If the padding property has four values:

- padding: 25px 50px 75px 100px;
    - top padding is 25px
    - right padding is 50px
    - bottom padding is 75px
    - left padding is 100px

<br />

**Element (like text,img... in the selector) properties for the box model include:**

- Height 
- Width

<br />
<br />

> An appropriate example on using the sytax for the above elements is as shown:
```css
/*styles.css*/
/*styles.css*/
.box_model {
    color: white;
    background-color: black;
    /* Primary tags to focus on in css box model*/
    padding: 50px;
    border: 30px solid red;
    margin: 100px;
    height: 20px;
    width: 100px;
    /*box-sizing: border-box*/;
    /* Additional styles*/
    text-align: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    font-size: 15px;
}
```
**Outcome**

[Refernce:Learn CSS Box Model In 8 Minutes](https://www.youtube.com/watch?v=rIO5326FgPE)

![css-box outcome](./resources/outcome_cssbox.png)

<br />


**Chrome-dev Tools**

Chrome-dev tools are a great help to visualize and make changes to the box and their design parameters. 

<img src="./resources/chrome_devTools.png" alt="chrome-dev tools" style="width:900px; height:auto">




#### References: 
1. [WDN: Mozzila Firefox](https://developer.mozilla.org/en-US/docs/Learn/CSS)
    - https://developer.mozilla.org/en-US/docs/Learn/CSS
2. https://www.youtube.com/watch?v=rIO5326FgPE
3. https://www.w3schools.com/css/css_padding.asp 