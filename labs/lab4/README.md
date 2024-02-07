# Insturctions for completeing Lab 4 
## Coding Hygiene

**Objective:**

Clean up this messy code. You're provided with a website that works just fine, but the code is a mess. This will both reduce the website’s SEO (Search Engine Optimization) and make it harder for your coworkers to help you maintain the website. Your job is to clean up the code. 

**Process:**
1. Start by reading [this short article](https://www.smashingmagazine.com/2008/11/12-principles-for-keeping-your-code-clean/ "article about clean html code") on the value of clean html code. 
1. Use the *index.html* file and the *images* folder to create your lab repository. Include the images inside the folder.
1. You are tasked with cleaning up the *index.html* file so that it looks (almost) exactly like the *lab4_final.html* file. Your alt tags should be the only difference. 
1. Begin your clean up by checking to see if the HTML5 Skeleton Structure is correct. 
1. Next, fix the abyssal indentation. Apply proper cascading. In our class, all children should be indented 2 spaces to the right of their parent element. Make sure to look at it in Github to see if there are any translation errors.
1. Now that your code is properly cascaded, it will be easier to find other errors. Check the following list of common errors. 
     * We never use ```<br>``` or ```<hr>``` to achieve line spacing. That is achieved using CSS. In fact, never use them as you are bound to use them incorrectly. 
     * Do the images have proper alt tags? Watch [this video](https://www.youtube.com/watch?si=ersf1RprfCrIUAGA&v=-jn9aaNn8_I&feature=youtu.be&themeRefresh=1 "vidoe about the value of alt tag") to learn the incredible SEO value of good alt tags (Hint: “Your alt tags will not match the final.html tags”).
     * We only use empty lines of code between semantic groupings of code. Like between ```<head>``` and ```<body>```, or between ```<section>```s.
     * Check to see if there are any obsolete ```<b>``` or ```<i>``` tags. Change them to the updated, semantic tags. 
     * There should be no space after the = sign in our attributes. Specifically, our links should be ```<a href="index.html">``` and not ```<a href = "index.html">```
     * There should be no space after html elements. Specifically, our p elements should be ```<p>```Hello World```</p>``` and not ```<p>```    Hello World    ```</p>```
     * Our links to files in our own repository do not need to start with (./). Specifically, href links should be href="folder/file.html" and not href="./ folder/file.html".
1. Follow the video instructions for testing and turning in labs (*How to Turn In Labs*).
1. **Improtant Validation Issues:** The html validation of a perfect lab 4 will still produce one warning and one error. 
     * The warning will be for "lang=". The validator doesn't recognize the generic Latin text used in the body. I will never take points off for a validation warning. They are recomendations. Some are good. Others can be ignored. 
     * The error is for the frameborder on the YouTube embeded code. Eventually we will learn how to use CSS to maintain a YouTube video's demensions. But not yet. So, for now we let this validation error slide.
1. Turn in the following:
    * Repo Link
    * Live Link
    * Image of Validation Screen Capture
    * Image of File Comparison
