# barthflo

My project0 is a fictionnal website about a travel tour company that I used when I visited Mongolia.
All the content pictures are mine.

I used SASS partials to organized my styles, with a master styles.css regrouping them all.
I used Bootstrap grid system to have a fully responsive layout and I used some of the Bootstrap components such as buttons, forms, collapse and carousel.
I used bootstrap script coupled with jquery and jpopper for the behaviour of some compnents in addition of short lines of Javascript.

My barthflo folder contains the 4 html pages, a CSS folder and my Image Library folder. The CSS folder contains all my SASS partials, my master SASS and the compiled mast CSS. My partials are listed as such : 
_main : contains my variables, typography, header and footer design and the collapse menu. They appear on everypages on my website.
_home, _tours, _gallery, _about : my pages content styles.
_mediaQueries : all my media queries for responsiveness.
The styles.scss is importing all of my partials.

index.html is my home page : use bootstrap grid layout for positionning my different sections. I am using images, text, bootstrap grp-button on small devices, a bootstrap carousel linking on different sections on my tours.html page, a link for a phone call, and a bootstrap form for the newletter.

tours.html is using bootstrap grid layout and an accordion system made with :hover css property. The accordion collapse from side on large devices and stacks on smaller ones. each collapsing menu contains a bootstrap button sending to my second section of my about.html page.

gallery.html is using a bootstrap responsive table for displaying a photo gallery. Each photo is clickable and display in a lighbox, which can be then view like a slideshow.

about.html is using a bootstrap grid layout. It contains images, texts and a bootstrap form. 

