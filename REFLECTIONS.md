Location: 
https://github.com/pitt-cdm/website--christyh310/tree/master/docs  (On GitHub)

https://pitt-cdm.github.io/website--christyh310/index.html (as a public GitHub Page)

For this project, I wanted to continue to discuss the Yakama Indian Reservation, and with a website, there is much more space available to tell a bit about some personal experiences and thoughts as compared to the other two projects. So, that’s what I intended to do. When I began, I wanted to talk about the trips I’ve taken and what I’ve learned as a result. I initially wanted to have three separate pages and a main page, which I thought would just have a picture and the title of the site on it: 
![image](https://user-images.githubusercontent.com/46638612/55045529-0c6fe480-500c-11e9-9698-63eb79f72862.png)
However, as I started to build my website with my own html code, I realized that the display/navigation, and styling that I wanted from my site could be much more easily (and smoothly) done with a template, so I began to work with the Spectral template. I did this because the dark colors would go with several of the pictures that I intended to work into my website. I also liked the unassuming, simple font and gently fading in main page that accompanied this site. Then, when implementing this template, the main page had room setup where I could place important content, and that meant I could remove the third subpage from my original plan, while still meeting the baseline criteria of three separate navigation locations.
Once I decided on a template, rummaging through the lengthy html and css pages to find what I needed to change was harder than I had anticipated; however, I was able to make some key changes. 

_Main background image adjustments_: I knew that I wanted to display one of my own images (the road and mountains image) as the main fading in image on the home page, but every time I tried to change the 'banner' selector, I realized that the image itself wasn't being edited there, but rather was a background image, and was being used throughout the entire main page, so was incredibly zoomed in; therefore, I needed to search using the finder to get just the background image within the body, and then I realized that there was many features (-mox-linear-gradient, etc) that were making the image zoomed in/spread out throughout the entire site, which isn’t how I wanted it to display. By fiddling with these sections and commenting out the parts that I didn’t want to display, I was able to get just right, and maintain the integrity of the image, scrolling features, and smooth transition the template offered!

![image](https://user-images.githubusercontent.com/46638612/55045543-17c31000-500c-11e9-9103-5e502838556c.png)

(notice that is editing the #banner ID, which is where (in the index file) the text I changed is also located.)

_Changing colors_: 
![image](https://user-images.githubusercontent.com/46638612/55045585-4214cd80-500c-11e9-854f-df9c7455cec4.png)
In order to change the background of the main header/disclaimer on the home page (index.html), I needed to find the appropriate class index, and change the color. Because of all the variations and additional modifications that are involved with the .wrapper.style1 class, this wasn’t easy, but I was able to figure it out after some troubleshooting! (I ended up modifying the color again after taking this screenshot, by just altering the hex code within the .wrapper.style1 background-color.)


After making edits to the main page, I wanted to see how the other pages visually directed the reader. I appreciated the contrast of the projects page (which was the “elements” page of the original template), because the white background and difference in style draws attention to the different content this page contains. This page shows projects I’ve worked on in our CDM class, while the other two pages are more focused on what I’ve learned in Yakama and what He has been showing me, so, the projects page is necessarily a different style. However, the white background was too bright and abrupt for the flow of my site, so I decided to change the color of the background of the projects page. To do this, I searched through the background-color features, to find which backgrounds were set to white (#ffffff), and was able to then match up the background of that particular class with the background I wanted to change! So, I changed it to a light blue (#b5d7f3). This .wrapper.style5 subclass has both the background and text colors defined within it, and then there are more detailed descriptions of the same class, for the strong or emphasized text, and for different buttons that were included in the template (some of which I removed to simplify the css code).

![image](https://user-images.githubusercontent.com/46638612/55045628-6a043100-500c-11e9-9bc3-fd49b8352cf9.png)

_Changing the menu color to match the main section color(s)_:
The original menu color was a bright turquoise, which I liked, but again didn’t quite fit the site, so I found and edited the color to match the other sections!! (#menu, background color)
![image](https://user-images.githubusercontent.com/46638612/55045638-74bec600-500c-11e9-891e-a062c5b15c3f.png)

_Removing and changing footer content_:
Lastly, I removed much of the footer’s content (I didn’t have a need to link to any social media from my website) and replaced the content with the title of my page. This was a simple edit, involving me just replacing some content and deleting it within the html pages themselves. 

![image](https://user-images.githubusercontent.com/46638612/55045642-7e482e00-500c-11e9-98b1-69d0bd7a623e.png)

_Added feature_: On the projects page, I wanted the user to be able to listen to an MP3 of my soundscape! I used https://www.apowersoft.com/embed-mp3-in-html.html and edited a snippet of code from here in order to add the MP3 to my site – the code given was repetitive, so I took the repetitive part out, and it works! I was trying to figure out why it still autoplays when the user navigates to the page, but I wasn’t able to figure out that attribute.

_Other edits_: 
Further, I made comments throughout parts of the main.css file to explain to myself and others what each part is doing, and commented out sections that didn’t apply to my site. 
Lastly, I was able to load my website publicly through Github Pages! Exciting!

_CSS classes explained_:
![image](https://user-images.githubusercontent.com/46638612/55045660-97e97580-500c-11e9-955b-3b0cbb2b7721.png)

This class defines the font and the spacing of the line of text of header type h3; so wherever this is used in html, it will have a certain font size and spacing associated with it. The unit em is relative to the font size of the element. 

![image](https://user-images.githubusercontent.com/46638612/55045671-9fa91a00-500c-11e9-8819-df286fe870a5.png)

This class defines what occurs when strong or b is typed in the html. When that occurs, the color becomes white, indicated by #fff. The font weight (or boldness) is 600. A typical “bold” is in the 500-700 range, so this makes sense. 

_Feedback_:
One piece of feedback was to possibly link the pictures on the main page to other parts of my website. I decided not to implement this feature because there is already a clear navigation menu, and because the pictures/text on the main page are about the site, but not about each subpage, and so linking to them in those locations wouldn’t help with the flow of the site. 

![image](https://user-images.githubusercontent.com/46638612/55045685-ad5e9f80-500c-11e9-87b6-de29bdc98298.png)

Another piece of feedback pointed out that some of my links between pages (mainly back to the Home (index.hmtl) page weren’t working. This was helpful, and because I only navigated away from the home page/got used to looking at it for a while, I wouldn’t have noticed this otherwise! Yay feedback! Also, this feedback mentioned changing the word “Spectral” to “Home” on the top left of the main page, so I did that, to and changed the side menu to match, so it looked more like my website, not the template.

![image](https://user-images.githubusercontent.com/46638612/55045695-b3ed1700-500c-11e9-9937-782499029b17.png)
![image](https://user-images.githubusercontent.com/46638612/55045699-b6e80780-500c-11e9-8be6-97a5981cac36.png)

