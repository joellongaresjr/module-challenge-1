# module-challenge-1!

# Description 
Welcome to my very first challenge. I'm very proud to be submitting this assignment, because prior to this I didn't feel confident that I would actually get the material. However, with a little bit of encouragement and guidance from the resources available from the bootcamp, I was able to execute enough to hopefully meet grading crieria! Thank you to whoever took the time to read that small bit, now let's dive deep into why I made the changes to our code.

Our objective of this assignment was to identify errors of HTML & CSS within a given code. Below you'll see several examples of what changes I made to the code to exectute the assignment!

# Code Refractor Examples 


My very first acknowledgement I made was realzing that HTML semantic elements were not labeled properly within majority of the code. Therefore, I attemptepted to label them accordingly. 

'''html 
<body>
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

My first attempt of fixing the code was the header.
I labled the semantic elements by identifying 1. <body> 2. <header> 3. <nav> (I used nav here to allow my code to know to navigate to the corresponding section within the browser)
-------------------------------------------------------------------------------------------------------------------------------------------------------------
'''html
<section class="content">
  **      <article id="search-engine-optimization" class="search-engine-optimization">**
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>
        <article id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </article>
        <article id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </article>
    </section>    

Here I fixed thke semantics by adding <section> <arctile>
I also realized that that 