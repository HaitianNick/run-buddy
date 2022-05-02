# **Responsive Web-Design**
* Features such Flexbox, CSS Grid, and Media Queries make up the key elements of 
responsive web-design.

* Responsive Web-design is the practice of creating web pages that respond to the type of
device requesting them.

* This practice ensures that a webpage will automatically adapt to a huge variety of 
devices without reqiuring developers to manage multiple code bases.

* **One way to increase the likeleyhood of succeeding in challening ventures is to 
anticipate obstacles before they show up and develop a plan for dealing with them.
To do this, try a simple strategy called ***WOOP: Wish, Outcome, Obstacle, Plan***.

* **WOOP** invites you to contrast positive events in the future with negative factors, or
*obstacles*, in the present that might stop you from reaching that future. Then you make a plan for overcoming these *obstacles* when they show up.

## **How to WOOP**
*WOOP* only takes a few minutes. Give it a try!

1. Start by visualizing your desired future for 3-5 minutes:
    *  First think about what you wish to happen.
    *  Consider the best outcome if you reach your goal. 
    * What will that mean for you?
    * How might your life be different?

2. Then, for the next 3-5 minutes, think about any present challenges that could preveng this future from happening. 
   * What obstacles might stop you from resaching your goal?

3. Lastly, make a clear plan about how to handle these obstacles when they appear.
   * Frame your plans like this: 
   ```
   "If...(obstacle happens), then I will...(action or thought)."
   ```

4. Write down your plans and keep them handy.
 

## WOOP for BootCamp (example):
### **1st. Desired result**
  1. Ability to create a fully functional web app and/or simple software from end to end
  2. Ability to webscrape
  3. Ability to Automate
  4. Ability to get into solidity and web3/nfts
  5. Ability to to be employed as a junior dev.

### **2nd. What is the best outcome if you reach your goals? What will that mean for you? How will life be different?** 
 * My best outcome is that I find meaningful employment with a company where I can learn and grow. Also to start a successful software solutoins company or start up.
 * What this means for me if completed is that i will officially know what I'm doing when it comes to coding. I can automate and webscrape wich transcends everything I want to do. I will be a professional, employable, and financially independent through either employment, my own endeavors, or both. Most importantly, solidify stability for my children and gaurantee thier safety. 
 * Life will be different because I will have all of my kids and extended family who wants, all under 1 roof if not, at least it will be another station for the family.*


### **3rd. Challenges**
1. 🕜 The Time it takes for me to learn the material
2. 🕥 The Time I have to devide between doing working living and learning.
3. The need for me to make money
4. My housing situation
5. No vehicle to help getting money easier.
6. The Law 👮

### **4th. Plan**
1. *For the time it takes me to learn the material:*   
   * Keep going. Don't stop. 
   * Find a more efficient way to learn the chapter.
   * I can use the pomodoro technique, etc.
2. *For dividing time between living, working and learning:*
   * If I don't have the adequate times available to do all that I must, I will improve my time management and energy skills. 
   * I will stick to the zak block schedule dailey.
   * Stop smoking 🌴. Use alternatives. Saves energy. 
3. *For the need to make money:*
   * I will consistently do PJ1st P on schedule like planned. 
   * I will use the 4hr zak slot on time every day in the most efficient way possible.
   * I stop using weed and sell the most exotic weed products
   * I will handle my legit business on schedule as planned.
   * I will put all money towards personal credit, business credit, leveraging credit, 
   and savings.  
4. *For housing situation:* I will rent a house. Then buy one. 
5. *For the car:* 
   * I will fix my credit and co-sign with my brother for a vehicle under 25k.
   * I will scrape 1st P money on a e-scooter/bycycle  if I have to.
6.*For the law:* 
   * Start paying attorney.
   * Use Jeff FG when I slide. If legal outcome pre-negotaited favorably, I turn myself in.



**Always remember** that you only have a problem if you don't have a solution. 

### **Use Woop heavily.** 
* Become Scrum Master. 
* Do Tech Project Management then get curriculum for Product Management.


## **FLEXBOX**
* Flex box is a one dimensional payout method to allow you to loayout items in columns and rows.

* In CSS everything has a box around it and the default display, which is what sets the box for the majority for the majority of all elements in CSS is block.

* We don't usaully declare "display: block" It's an inherited property from the user agent in the browser.

* The page on the screen is currently set up using the box-model. 
* And the boxes on the screen are inside of a container section that has "display: block" as a CSS attribute.

## **display: flex**

* Because I used `display: flex` the container has now become a ***flex-container*** and this gives us a new set of rules for layout and positioning to use in our CSS.

* Now the boxes, which are direct children inside of the *flex container*, are now considered to be ***flex-items***. And the boxes can now be positioned based on these inner roles.

* Whenever you have a *flex-box*, ***the default direction of all items inside the flex-box is a row***, which means that everything will line up along a **horizontal** axis. Now the items directly inside of these boxes **aren't** affected by flexbox. Its only the direct children that are affected by flexbox.

`Justify-content`- Defines alignment along the main axis. Since the default direction for flexbox is `row`, this alignment will be based on the **horizontal** axis.

`justify-content: center`- My *flex-items* are now centered along the row.

The **verticle** axis, flexbox treats as a column, `align-items: center`

`align-items` is centered based on the container `height` *pixels value*.
If there is no declared `height`, `align-items` moves up to the top because now the `height` is based on the *available space* and no longer a fixed value.

`flex-direction: column` - Allows you to use the *verticle* axis instead of the default *horizontal* axis for all our layout and positioning properties.
When we use `flex-direction: cloumn`, `justify-content` and `align-items` swap positions

`justify-content: space-around` - Causes each *flex item* to have a equal amount of space of both the left and right side of container. This causes the appearance of the ends to have a half size space. 

`justify-content: space-between`

`justify-content: space-evenly`

`flex-wrap: wrap`- By default *flexbox items* will try to fit on a single line. When wrap is used, if the items can't fit in one line, they will wrap to the next line.

* You can change the `width` to force the situation. If the box too big for a single line so it can wrap to the next line.

The **flex CSS shorthand property** sets how a *flex item* will grow or shrink to fit the space available in its flex container:

* `flex-direction` sets how *flex items* are placed in the *flex container* defining the **main axis** and the **direction** (*normal or reversed*)

***Responsive Web Design*** is a set of practices that allows web pages to alter their layout and appearance to suit different screen widths, resolutions, etc.

***Media Queries*** allows us to run a series of test and apply **CSS** selectively to style the page appropiately for the user's needs. The **CSS** will only be applied if queries are true.

* You can add multiple queries to your stylesheet, tweaking the whole layout or parts of it to best suit the various screen sizes.

The points at which a *media query* is introduced and the layout changed are known as ***breakpoints***.

## **MOBILE FIRST DESIGN**
A common approach when using **Media Queries** is to create a simple *single-column layout* for narrow-screen devices (e.g mobile phones), then check for larger screens *width* to handle it. This is often descibed as **mobile first design**.

## **FLEXBOX GRIDS**
Responsive sites are also built on *flexible grids*. 
A *flexible grid* means that *you don't need to target every possible device size that there is*, and build a pixel perfect layout for it.

By using *flexible grid*, you only need to add a *breakpoint* and change the design at the point where the content starts to look bad.

Ethan Marcotte's Formula for taking a layout design using pixels and converting to percentages:

    target / context = result

For example, if our *target column size* is 60 pixels, and the content( or container) it is in is 980 pixels, we divide 60 by 980 to get a value we can use in our CSS, after moving the decimal point two places to the right.

```css
.col {
  width: 6.12%;      /* 60 / 980 = 0.0612 */
}
```


### **MODERN LAYOUT TECHNOLOGIES**

Modern layout methods such as *multiple-column layout*, *flexbox*, and *Grid* are ***responsive by default***.


`Multicol`- When you specify a `column-count`, this indicates how many columns you want your content to be split into.
The browser then works out a size that will change according to the screen size.

```css
.container {
  column-count: 3;
}
```

If you instead specify a `column-width`, you are specifying the *minimum width*. The browser will create as many columns of that width as will comfortably fit into the container, then share out the remaing spaces between all the columns. Therefore the number of columns will change according to how much space there is:
```css
.container {
  column-width: 10em;
}
```


Flexbox


Multi-Column Grids





The sign-up form (on Run Buddy) was declared with `position` absolute 


























Implement a stack data structure where the last item (push) is the first item out (pop).
305-471-5080

text MGW


AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

commmit:

double checked that all links work perfectly
Applications CSS selectors are consolidated
Applications CSS file is properly commented


Application is now deployed at live URL




The application URL is live deployed and the link is in the readme.
All links work perfectly
Application's CSS selectors are consolidated
Application's CSS file is poperly commented.


Application is deployed at live URL
https://github.com/HaitianNick/urban-octo-telegram

Application loads with no errors

Application GitHub URL submitted
https://haitiannick.github.io/urban-octo-telegram/

The application resembles 90% of the screenshots provided


link to project
https://github.com/HaitianNick/urban-octo-telegram

link to live site:
https://haitiannick.github.io/urban-octo-telegram/




You use the .this keyword to reference objects within itself




A promise is a javascript object that might produce a single value in the near future.

The function is going to promise you that in the near future whenever the code is finished, it is going to notify you and give you a result.


The promise receives a function of resolve and reject

Promises have three possible states:

Pending, Fulfilled or rejected

Whenever we call our promise, it is going to start in a Pending state

timer is set to resolve the promise
This resololve is going to change the state of our Promise to 'Fulfill'

Whenever you want to do something with the result that your getting from your promise, you can use a '.then()' which is going to execute after your code has been resolved

The 'value' in the .then() function is the resolved state of our promise


var promise = new Promise(function(resolve, reject) {
    setTimeout(function() {
        resolve("codingsrc");
    }, 3000);
});

promise.then(function(value) {
    console.log(value);
});



HANDLING REJECTED STATES OF PROMISES

The 1st way is to call the promise and type .then() and provide not 1 but 2 functions.

The 1st function is going to handle the 'Resolve' state of your promise,
The 2nd function is going to handle the 'Rejected' state of your promise.

```js
promise.then(
  function(result) {

  // on Fulfilled
  console.log("Success!")
},

function(error) {
  // on Rejected
  console.log("Failed");
};
```




### Town Take Over:

This is not in order. I will find a high-density area and make: 
* A trap first.
* After 90days find another spot to duck off
* After I duck off, get 2nd trap/storefront
* After I .
* After 2nd trap/storefront, purchase home, Farm, timeshare, overseas emergency get away.

