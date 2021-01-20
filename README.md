# Little Paradise - Band Website

## Code Institute's Milestone Project 1 - User Centric Front-End

![Hero image of website across screen sizes](assets/images/amiresponsive.png)

Little Paradise are a musical duo who write and record songs from a home studio in Bristol. Having spent the best part of a year on creating new music, the band (of which I am one of the two members) has decided to build an online presence now that musical content is ready to be released to the world. My aim with this project is to create a website which can act as a convenient and memorable hub of music and informative content for users to consume. The website achieves this goal with combined functionality that is not readily available or as visually appealing on standard social media platforms such as Facebook.
 
The project is the first of four ‘milestone’ projects which are required to complete the Code Institute’s diploma in full stack web development. Assessment criteria for this milestone project focusses on the ability to produce a static, responsive front-end site using HTML and CSS learnt during the first part of the course.

You can view the live website [here](https://franciskershaw.github.io/little-paradise-music/index.html), and a link to the github repository can be found [here](https://franciskershaw.github.io/little-paradise-music/index.html)

## UX

***

My main goals for the creation of this website were as follows:

* Create a centralised platform that includes all of the features needed to start and nurture online engagement with a new music band.
* Create an aesthetically appealing website that leaves all users with a positive emotional response, regardless of whether their visit will convert them into fans of the band’s music or not.
* Demonstrate my new found competence in applying HTML and CSS to independently coded projects so as to meet the pass criteria of the Code Institute for this milestone project. 

### **User Stories**
 
#### **Band member (project *stakeholder*)**

As a member of Little Paradise:

1. I would like people to listen to and/or buy our music in order to gain new fans.
2. I would like fans to know about upcoming tour dates so that they can buy tickets to gigs.
3. I would like to contact fans directly via email updates so that we can inform them about new releases, tour dates or general band news.
4. I would like booking agents or record labels who end up on our site to find contact details if they want inform us of any opportunities. 
5. I want potential fans to find our social links so that we can increase followers and engagement on our social platforms.
6. I want anyone who visits the site to have a positive emotional response to the layout of the site and branding, in order to make a lasting impression that sets us apart from other new bands. 

#### **Users**

1. As someone who has never heard of Little Paradise before, I would like to listen to the band’s music to help me decide if I should keep tabs on them.
2. As an existing fan who has already heard the band’s music before, I would like to know about any upcoming tour dates so that I can consider watching them live.
3. As an avid fan who has a keen interest in the band’s music, I would like to see photos and find out more about the band's history so that I can feel a slightly more personal connection to them away from the music.
4. As a booking agent or record label, I would like to easily find contact details so that I can directly approach the band regarding potential gigs or collaboration opportunities they might be interested in.

## Planning & Design

***

### **Strategy Plane** - *What are you aiming to achieve in the first place and for whom?*

The **user stories** as detailed in the previous section was the first part of the development process and was very helpful in deciding which features were critical to the success of the site. Features that I did not deem necessary to the band and users reaching the end of their journeys would not be considered.

The **focus** of the project is: 

* To provide Little Paradise (the stakeholder) with an area to consolidate relevant information about the band for fans and booking agents and to ensure all visitors reach the end of their user stories.

The **business goals** for the stakeholder are to:

* Create an online presence which will increase exposure and gain new fans. 
* Sell tickets to shows and music.
* Nurture new relationships with fans through email updates.

*The band therefore needed a bespoke website, as the current options provided by social media platforms are insufficient and too general to achieve their goals.*

While strategising, I researched as many band websites as possible and continued to use them as references throughout the development process. This was to ensure that I would remain consistent with the familiar conventions applied to band websites while ensuring my own goals were met. 

The following sites proved to be very useful when considering the features that would best help fulfil my user stories:

* [Foals](https://www.foals.co.uk/)
* [Palace](https://www.wearepalace.com/)
* [Bandzoogle Sample Sites](https://bandzoogle.com/sample-band-sites)
  * [Emily Kinney](https://emilykinneymusic.com/)
  * [Ships Have Sailed](https://shipshavesailed.com/)
  * [Scilla Hess](https://scillahess.com/)
  * [Flagship Romance](https://flagshipromance.com/)


Using the below importance vs viability metric, I could see that the available opportunities to fulfil my user stories were mostly achievable, relevant and appropriate. It did however help me quickly conclude that selling merchandise, while being a common feature across most band websites, was as unnecessary to have at this stage in the band's career as it was difficult to implement. Likewise, during research I found that several websites included sections for their song lyrics, which I felt would contribute to content overload in my case and not help achieve any of my user stories.

Opportunity | Importance | Viability
------------ | ------------- | ------------- 
Create an online presence | 5 | 5
Have a gallery of photos | 3 | 4
Have a list of upcoming tour dates | 3 | 5
Showcase existing music | 5 | 3
Provide contact details | 4 | 5
Sell merchandise | 2 | 1
Provide song lyrics | 1 | 5
**Total** | **23** | **28**

### **Scope Plane** - *Which features, based on information from the strategy plane, do you want to include in your design?*

Based on information I uncovered in the strategy plane, and considering any limitations of my current coding abilities, the features I decided were critical to include are as follows:

**Required Functional Specifications**
1. At least one section on the site to listen to music.
2. A section for upcoming tour dates.
3. An area to find out more about the band's history.
4. A photo gallery.
5. A dedicated area to find out contact information or sign up to email updates.

**Content Requirements of these features**

1. Music content must be easy to find and come from a variety of available and familiar music platforms.
2. Tour dates must provide concise, relevant information as well as links to buy tickets.
3. Bio section should be entertaining and informative.
4. Any photos must be of good quality and engaging.
5. Contact information must be easy to find.

### **Structure** - *How is the information structured and how is it logically grouped?*

Bearing in mind the functional and content specifications outlined in the scope plane, I decided to create five unique pages for the site that could share responsibility for hosting the necessary features. 

1. A home page which draws the user in with a striking hero image, contains two call to actions directing users to the most highly prioritised content (music and email updates), and includes upcoming tour dates.
2. A music page that includes the currently available platforms through which a user could listen to the band’s music (SoundCloud and YouTube) and a section for available releases.
3. A gallery containing various photos of the band members.
4. An about page which tells a brief history of the band up until present day.
5. A contact page (including sign-up option) to find contact details and sign up to email updates

#### Interaction Design

* A nonlinear structure (achieved via a fixed navigation bar on each page) was needed in order to allow users to pick and choose sections they wish to navigate at any point during their journey.
* Navigation links, as well as any other buttons or links as part of a page’s content, needed to change colour when hovered over or clicked on to provide user feedback
* The same colour scheme and design themes are applied across all pages to maintain consistency
* Where possible, secondary content on the page needed to appear just beyond the fold on as many screen sizes as possible to highlight the fact that the page can be scrolled through
* A footer would provide social links and remain consistent across all pages

#### Information Architecture

* Tree structure with use of navigation’s burger icon when on mobile devices
* Priority on the navigation bar will go from left to right 
* Logo on the far left and features on the far right in the following order of perceived importance: Tour, Music, Gallery, About, Contact
* The most important features will manifest in the CTAs: A link to buy new music + a link to sign up for email updates

### **Skeleton Plane** - *How will our information be represented, and how will the user navigate to the information and the features?*

In order to properly visualise how my pages would be organised and linked together, I created some low fidelity mockups using InVision - focussing on the design layout for small, medium and large screen sizes. The purpose of this process was to double check that the ideas I had begun formulating internally during the structure plane would be faithful to the user stories they were designed to fulfil. This way, if any obvious issues did arise it could be fixed well before coding of the pages started in earnest. 

For the most part, I felt satisfied at this stage that all my user stories would in theory be completed intuitively through the layout of my site. I did however spot during this process that users in my first user story (who would be arriving primarily to consume music) may be frustrated that no musical content appears on the home page at all. This was rectified in the final version of the site by including a small section below the primary call to actions which contained the same YouTube iframe present in the music page with a link to the music page for those who want to hear more.

![Hero image of website across screen sizes](assets/images/index.png)
![Hero image of website across screen sizes](assets/images/music.png)
![Hero image of website across screen sizes](assets/images/gallery.png)
![Hero image of website across screen sizes](assets/images/about.png)
![Hero image of website across screen sizes](assets/images/contact.png)

### Surface plane - *What will the finished product look like? Colors, typography and design elements*

Little Paradise has never had an online presence or brand before the creation of this website, so deciding what kind of aesthetic to employ was not dictated by any pre-existing brand requirements or colour schemes. This provided a challenge, but also a great level of creative freedom to work with.

The starting point for what the look and feel I would end up pursuing came from an accidental discovery of the ‘Syne Mono’ font on Google Fonts. This minimalist typography instantly grabbed me as unique, and in a way ended up informing many of the stylistic decisions that would be taken across the website. I decided to stick with a mostly black, white and grey colour scheme to complement the retro vibe that is given off by Syne Mono, and a smattering of red can be found assigned to important features - such as the call to action buttons or when hovering over navigation links. The main idea behind this was to maintain a small amount of mystery around the band and its members, which was further personified by a bespoke hero image (kindly provided by Izi Thexton) portraying the band members as faceless black and white drawings.

Animations/transitions/effects
