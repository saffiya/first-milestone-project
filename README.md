<h2>The Monkees Band</h2>
I created this website for the fans/potential fans of the monkees.

The website highlights their:
<ul>
<li>Upcoming tour dates</li>
<li>Music</li>
<li>Music videos</li>
<li>Latest news about the band/band members</li>
<li>Availabilty to play at events</li>
<li>Information on the band and how they came to be</li>
<li>Pictures of the band</li>
<li>Social media accounts</li>
<li>Band members and what they play</li>
</ul>

<p>By adding all this information on the site, it is hoped all users, young and old,
will find it easy to navigate; finding all that they desire without having to travel elsewhere.
An illustration of this is demonstrated by the way music videos and spotify playlists have been placed on the site;
to supersede a link for the user to follow which would have taken the user out of the site.
Instead, the user can press play to listen and then click on the next page or thing that they want, thereby making the site extremely efficient.</p>

<h3>UX</h3>
<p>The goal for this design was to make it as easy as possible to access information on the site, whilst striving for a simple yet fun design.
The color scheme was inspired by the bands love for color and boldness.
Red, my main starting color, is used consistently by the band. 
This color can be seen on the homepage. It was placed there as its very eye catching and i believe it will lure users to check out the rest of the site.
The Adobe Kuler was used to find complementary shades; used throughout the rest of the pages; giving the site a complete view/look.</p>

<p>For fans and potential event co-ordinators, i wanted to provide them with a brief overview of the band and how they came to be;
while showcasing who they are and what they have created. 
A Book Us Now button has been attached to enable the viewers to hire them for events.
By attaching this button to the site it shows their availabilty to perform; and by filling out the modal form attached, the band manager will be able to get in contact with whomever would like to book them.</p>

<p>There is an email form and subscribe button attached where fans can sign up to recieve concert, tour and band updates. Therefore fans are always informed of anything new happening; making the user feel more connected to the band.</p>

<p>Below is a link to my wireframe; which was designed to make my website easier to build upon; I have followed the design of my wireframe very closely and only made minor changes.
https://balsamiq.cloud/s8d4pq3/pkgvge7 </p>

<h3>Features</h3
<ul>
<li>The Site uses a navbar that collapses into a burger icon on smaller screens taking up less retail space.</li>
<li>A Book Us Now button is used alongside a modal form which was added from bootstrap.</li>
<li>A email form and suscribe button has been added to the footer of the first page.</li>
<li>Social media icons with links to the monkees page on each platform has been added to the footer of each page, So that the users can easily follow them.</li>
<li>A youtube video has been placed in the music page using an iframe, for the user to watch.</li>
<li>Spotify playlists have been added using iframes, so that users are able to listen to their music.</li>
</ul>

<h3>Features left to implement</h3>

In the future, I would like to add instagram and facebook pictures onto the gallery page.

<h3>Technologies Used</h3>
<ul>
<li>Adobe color: to find complementary shades to go with red (#dc3545). The complementary HEX codes were used across the entire site.</li>
<li>Bootstrap: to help with the html code behind modals, navbar and forms; i built upon the html found in bootrstrap within my site to get the layout and style desired.</li>
<li>Hover.css: the CSS codes found here were nvery helpful when adding shadow to the table in the tour section of the site.</li>

<h3>Testing</h3>
The site was tested across multiple browsers:
<ul>
<li>Safari</li>
<li>Yahoo</li>
<li>Chrome</li>
<li>Internet Explorer</li>
</ul>

Also on multiple mobile devices:
<ul>
<li>IPhone 5-8</li>
<li>Iphone X</li>
<li>IPad</li>
<li>IPad Pro</li>
<li>Galaxy S5</li>
<li>Pixel 2</li>
<li>Pixel 2 XL;</li>
</ul>
to ensure compatability and responsiveness.</br>


<p>During the testing stage the following was found:</p>
<ul>
<li>The text from the latest news section did not look right next to the image on mobile devices; therefore i placed the text just below the image of Peter Tork.</li>
<li>The latest news section kept drifting upon my first image on the home page; to fix this the removal of all the html code i had wrote to position the image was crucial.
The code was replaced with a top-img id and followed by some fundamental css; which kept the image in place. The changes made here were then duplicated for the events-background image, and the about page first image; Which revealed a much more polished look.
<li>The Book Us Now button was drifting to the top of the page, therefore the percentage of alignment had to be changed to accomadate smaller devices.</li>
<li>The Pictures of each band member on the about page did not fit well across the page on smaller devices; it became neccessary to place them below each other on smaller devices.</li>
<li>On the Tour page there was padding that was making the boxes go unaligned on smaller screens; therefore the padding was removed.</li>
<li>On the music page it was overwhelming to have 3 playlists on smaller screens, which made it quite difficult to operate that page. Now on smaller screens there is only one playlist; on medium screens there are two playlists and on large screens there are three.</p>
<li>The youtube video on the music page covered the entire page as soon as you clicked on the music button, so i had to offset the video in my css;
<li>The gallery page was completely squashed and looked horrid on smaller screens, therefore it was neccessary to change the layout.</li>
Now on smaller screens, instead of there being four images on one row,there is one per row and you scroll for more.</li>
By conducting all these tests i have made sure that the site works perfectly on all screen sizes.
<li>The modal form was not validated, therefore i adjusted the html so that they were.</li>
</ul>

<p>If you try to submit the Book Us Now modal form with an invalid email address, there will be an error noting the invalid email address.
The 'required' attribute has been added to the follwing fields:
<ul>
<li>name</li>
<li>email</li> 
<li>address</li>
<li>type of event</li>
<li>contact number</li>
<li>city</li>
<li>country</li>
<li>postcode</li>
</ul>
As a result; if those fields are not filled in, the form will not submit. 
If all fields are valid, the page will reload. If anyone wants to book the band to play at their event they need to fill out this form as those details are extremely relevant.</p>

<h3>Deployment</h3>
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch.
In order for the site to deploy correctly on GitHub pages, the landing page has been named index.html.

To run locally you can clone this repository directly into the editor of your choice by pasting git clone
https://saffiya.github.io/first-milestone-project/ into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

<h2>Credits</h2>

<h3>Content</h3>
The text for the latest news section was copied from the monkees site about Peter Tork.
https://www.monkees.com/article/rip-peter-tork

The text used in the about page was taken from wikipedia.
https://en.wikipedia.org/wiki/The_Monkees

The tour information was taken from the monkees site.
https://www.monkees.com/article/monkees-2019-tour-dates

<h3>Media</h3>
The photos used in this site were obtained from the assets folder, provided to me from the GitHub repo; received when i was given my brief.
A few images were taken from google using the filter 'free to share and use' section, therefore avoiding any copyright.

<h3>Acknowledgements</h3>

The spotify playlists was taken from https://developer.spotify.com/documentation/widgets/guides/adding-a-spotify-play-button/
