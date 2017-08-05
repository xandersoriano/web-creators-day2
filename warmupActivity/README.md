# Web Creators Day 2 Warmup Activity

## Mini Challenge 

See if you can update your Trillium home page to look like the picture below: 
![Trillium With List](images/trilliumWithList.png)

We are now going to use CSS (Cascading Style Sheets) to make our webpage more appealing. 

1. Rename `style.css` to `trillium.css` and delete all the text inside it. 

2. Add a link to your new `trillium.css` in your HTML files. This allows your HTML to "see" the CSS and apply the changes. 
![Link CSS](images/linkCSS.png)


3. Add these styles to your into your trillium.css file:
![Initial Styles](images/initialStyles.png)

Your webpage should look like this now:
![Trillium Initial CSS](images/trilliumInitialCSS.png)

## Classes and IDs

### Configure the CSS

4. Create a class name `feature` that configures red (#FF0000) text. Add the following code **TO THE BOTTOM** of your `trillium.css` file:
![Feature CSS](images/featureCSS.png)

Classes are used to configure multiple html elements 

5. Create an id named `content` that configures an off-white background color. Add the following code **TO THE BOTTOM** of your `trillium.css` file:
![Content CSS](images/contentCSS.png)

IDs are used to configure a **SINGLE** html element

### Configure the HTML

**CHANGES 6 and 7 GO INSIDE YOUR HTML FILE**

6. Modify the last two `<li>` tags in the unordered list. Add a class attribute that associates the `<li>` with the `feature` class. 
![Feature HTML](images/featureHTML.png)

7. Modify the opening div tag (located below the closing nav tag). Add an id attribute that associates the div with the id named `content`:
![Content HTML](images/contentHTML.png)

### Span 

8. Create a class name `companyName` that will configure the color of our company name in our paragraph. Remember to put it at the bottom of your CSS file. 
![Company Name CSS](images/companyNameCSS.png)

9. Now modify our paragraph in your HTML file so that our company name is now associated with it's class. 
![Company Name HTML](images/companyNameHTML.png)

### One Last Tweak 
I don't like the space between the header and the nav bar. Let's adjust the margin so that they're closer. Modify the h1 selector in your CSS file to look like this:

![H1 Margin](images/h1Margin.png)

Your page should now look like this:
![Trillium Final](images/trilliumFinal.png)


