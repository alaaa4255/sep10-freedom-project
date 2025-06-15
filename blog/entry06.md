# Entry 6,
##### 6/14/25

### Content:
<p>I have been working on my freedom project for the whole year. From gathering information about the softwares and hardwares that are used regarding my topic to finding a tool to practice/ tinker with to use while coding my website. I first started coding my website by planning how and where I wanted the content to be and look like. So, I did that by putting my ideas on a wirefrime. However, on the wireframe I had to create an outline of how my websites would look on mobile and on a computer. For the <a href=https://docs.google.com/drawings/d/1r4yVXYgeV1wT33aws_0JUshOaGTp32ZOCtafafKZdFI/edit> computer wireframe</a></p> I outlined my wbeiste to have all the containers lined up next to eachother and on top of eachother. For the navbar, I wanted it have a drop down to the softwares sections, Hardwares section, carousel, and Intro section. I wanted the Intro to be right under the navbar, then the hardwares under the intro, the carousel under the hardwares that would show the type of hardwares business use, then wouuld come the softwares that had the links to websites businesses use to operate, finally the external link to show off the tool I used. I had the same plan outlined for my <a href=https://docs.google.com/drawings/d/1XqemlZnF1lULrPYNrcSZyMoe9gIzjgeFQSZUTQ0NN_k/edit> mobile wirefarme </a> expect I had to rejust some of the content around. For the navbar, I made it where if it was put on a smaller screen like a phone, it would have three lines stacked on eachother, when pressed it would show the options of the conent in the webiste that would take them to that specfic section. for the containers, instead of three of them being lined uo against eachother it woild be 2 next to eachother. Everything else stayed the same. After planning that out, I took all my ideas and coded the final project/website. For coding I used, HTML, CSS, and bootstrap. For HTML I used fonts like Ariel, bold, thick letters. Fpr css, I used the color scheme of blue, grey, white, and black. For bootstrap, I used Navbar, carousel, and containers. I started coding in order, navbar, container (Intro), Hardware containers, Carousel, software containers with the links to the webistes in it, then the external link to the design I made using my tool. 

### Engineering designing process: 
<p> Coding my freedom project taught me so much. And with everything I now know, I am prepared to use all my skills as practice so that next year I could design something 10 times better than what I did this year. My next steps is to contnue learning about software and to get better by time. </p>


### Challenges:
<p> I faced many challenges while making my website, most had to do with the code itself. I struggeled with aligning the content, perfecting the navbar on mobile, and coding the A-frame.</p>

### Aligning:
<p>Making sure that the alignment of the conent in my website was perfect was really hard. There was always something causing it to colapse or not be the way I wanted it to be. For exaample, some containers were closer to eachother than the others. Then there was vertical containers that always collapased. These two problems happened because of a couple of reasons. For when some containers were closer to each other than the others were it was because of the padding, borders, size, etc. So, to fix that to the best way I could, I fixed the padding and szie and made them exactly the same so that they could be the way it should be. For when the containers kept on collapsing, it was because I didn't have the divs stacked or spaced out properly. So when i fixed that issue, the containers became the way I wanted them to be. </p>

```  <section id="software">
      <h2>SOFTWARE</h2>
      <div class="software-section">
        <!-- Software Cards -->
        <div class="container-bordered container-link">
          <div class="link-title"><a href="https://onpay.com" target="_blank">ONPAY</a></div>
          <ul>
            <li>Automates employee payroll and taxes.</li>
            <li>Handles global payments and time tracking.</li>
            <li>Keeps finances organized.</li>
          </ul>
        </div>
        <div class="container-bordered container-link">
          <div class="link-title"><a href="https://monday.com" target="_blank">MONDAY.COM HR</a></div>
          <ul>
            <li>Manages hiring, time tracking, and payroll.</li>
            <li>Streamlines onboarding and reviews.</li>
            <li>Supports HR automation.</li>
          </ul>
        </div>
        <div class="container-bordered container-link">
          <div class="link-title"><a href="https://clickup.com" target="_blank">CLICKUP</a></div>
          <ul>
            <li>Helps manage large projects efficiently.</li>
            <li>Improves team productivity and deadlines.</li>
            <li>Works for complex workflows.</li>
          </ul>
        </div>
        <div class="container-bordered container-link">
       <div class="link-title"><a href="https://www.zoho.com/crm/lp/lasting-customer-relationships.html?utm_source=forbesadvisor&utm_medium=cpl&utm_campaign=zcrm-review-fa" target="_blank">ZOHO.CRM</a></div>
       <ul>
           <li>Supports marketing and sales teams.</li>
           <li>Helps personalize marketing and track leads.</li>
           <li>Manages customer interactions.</li>
       </ul>
   </div>
</div>
```

### Navbar on mobile:
<p> When it came to coding the navbar, the main issue was how the navbar when pressed on a specfic section, showed both content when clicked to show a specific one. This issue was mostly because of the links to each section being too close to eachother. So to fix that I had to rejust the codingof the navbar and postiton the links where thry weren't going to continue giving me the same issue over and over again.</p>

``` <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Business '25</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#intro">Intro</a></li>
          <li class="nav-item"><a class="nav-link" href="#hardware">Hardware</a></li>
          <li class="nav-item"><a class="nav-link" href="#software">Software</a></li>
          <li class="nav-item"><a class="nav-link" href="#images">Images</a></li>
        </ul>
      </div>
    </div>
  </nav>
```
### A-Frame:
<p> My hardest challenge throughout the whole process of desgining my website was coding my A-Frame design. A-Frame was hard because Coordinates and rotations had to be perfect or design wouldn’t be clear or show, the Camera control, moving around sometimes was not active, and it would glitch. So, for the cordinates and rotations I had to make sure that the numbers all added up. I used google to help me. Then came the cameera control. Sometimes, the moving around would glitch or wouldn't be active. SO I fixed that by using the proper a-cameera and a-entity set up. </p>

``` <a-entity id="cameraRig" position="0 1.6 6">
       <a-camera wasd-controls="enabled: true" look-controls="pointerLockEnabled: true"></a-camera>
     </a-entity>
```

### Takeaways: 
<ul>
 <Li>Planning before you start coding will make the process go by easier </Li> 
<Li>constantly checking on your design while coding will help you keep track to all changes (good or bad) </Li>
<Li>keep track of how many divs you put </Li>
</ul>

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
