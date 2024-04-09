
# waph-shaikhl
# WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung

## Student

**Name**: Hadeel Shaik

**Email**: shaikhl@ucmail.uc.edu

**Short-bio**: I have keen interests in web development and secure software development. 

<img src="img/profile.jpg" alt="Hadeel's headshot" style="width: 150px; height: 150px;">
    
## Repository Information

Respository's URL: [https://github.com/shaikhl-12/waph-shaikhl.git](https://github.com/shaikhl-12/waph-shaikhl.git)

This is a private repository for Hadeel Shaik to store all code from the course. The organization of this repository is as follows.


Overview and Requirements:

This personal website shows skills, projects, and contact info. To make the site work on all devices, it uses CSS Bootstrap. It also uses JavaScript for basic functions. The site has two main parts:

**Section 1: Basic JavaScript Implementation**

The first part uses basic JavaScript functions to improve user interaction. This adds things like a digital clock, analog clock, show/hide email, and other features. To make sure the site adjusts well on different devices and screen sizes, it uses CSS Bootstrap.

**Section Two: Incorporating APIs and Advanced features**

The next part is about adding APIs to the site for more functions and data. An API like weatherbit.io is used to show real-time weather. The project also looks at using React.js for more complex features and better interaction. Cookies store session data to improve user experience across visits.

Here is a link to the project code on GitHub.
https://github.com/shaikhl-12/waph-shaikhl/edit/main/README.md

**General requirements:**
1.I made a professional site using open-source Bootstrap. Here's a screenshot of the index.html file hosted on GitHub.
    ![Picture 1](./img/1.png)
  	![Picture 2](./img/2.png)
  	![Picture 3](./img/3.png)
  	
2. I created a new HTML page called Waph.html and linked it to the main index.html file so that users could access the extra web page content from the primary homepage

At first, I connected the Waph.html page by adding an anchor tag in the section about education. In the explanation of my master's program, there is a selection for web programming and security testing. Selecting this choice displays the Waph.html document. Shown below is a picture demonstrating this operation between files.
 ![Picture 3](./img/4.png)


**Non-technical requirements:**

1.	CSS Bootstrap: I used CSS Bootstrap to make the website responsive and aesthetically pleasing. I integrated open-source code libraries to achieve this. The elements automatically adapt to fit different display screen dimensions.
  
2.	Page Tracker:I set up website usage tracking by embedding Google Analytics, letting me record visitor statistics. I first registered my site on the analytics.google.com platform to activate the monitoring.

After connecting my webpage to the Google Analytics tool, some time elapsed before the traffic analytics began capturing data. Once initialized, I could access visitor and usage reports from the main dashboard. Below is a screenshot demonstrating this:
![Picture 3](./img/16.png)

**Technical requirements:**

**Basic JavaScript code**

1.	Digital Clock: I used the React.js library to create a digital clock feature. I built a reusable component in a React application to display the clock interface, then compiled the project into a standalone JavaScript file. I incorporated that file into my main website project within index.html. I imported the required React and ReactDOM libraries.

Shown below is a screenshot demonstrating the digital clock displayed on the live webpage, which was integrated through the React component
    ![Image](./img/5.png)
    
3.	Analog Clock:I reused the analog clock JavaScript code as-is from a previous lab to display a clock face on my site. The code draws clock hands rotating around a center point to show the current time. Below this is a screenshot exhibiting the same analog clock visualization. 
   
    ![Image](./img/6.png)
    
5.	Show/hide your Email: I reused the JavaScript code from a previous lab that displays hidden text when clicked, implementing it in my contact page. The script allows clicking a label to toggle revealing content underneath. As shown in the following screenshots, this makes my email address appear when activated on the live site contact segment.
   
    ![Image](./img/13.png)
  	
    ![Image](./img/14.png)
   
Additional functionality: I used basic JS validation code to check the contact form inputs.  When submitting the form, a function checks the input fields are filled out properly.

a.	Shown below is the error message displayed when invalid or missing email fields are attempted.

b.	Here is the screenshot displaying error message when invalid details are given. 
  ![Image](./img/15.png)


**Web APIs integration:**

1.	Integrating the Joke API: I also integrated an API random joke generator similar to a previous lab, displaying a retrieved joke at the bottom of my webpage as demonstrated in the screenshot..
    ![Image](./img/9.png)

3.	Integrating a public API with graphics: Additionally, I utilized the weatherbit.io API to show current weather and associated icons in the header.  The JavaScript makes a call to the weather API from within index.html.
   
This allows displaying the current temperature and matching weather symbol in the navbar, as seen in the screenshot. :
     ![Image](./img/10.png)


**JavaScript Cookies:**

Cookies store user data across sessions. I used cookies to show different welcome messages to returning users or new visitors.  The first-time welcome banner differs from the message for recurring visitors as shown in the below screenshots.

The first set of images display the initial welcome when first logging in to the website. 
  ![Image](./img/11.png)
  
The second screenshot then exhibits the modified message if visiting again from the same browser.

  ![Image](./img/12.png)


Here is the website URL :  https://shaikhl-12.github.io/shaikhl/





