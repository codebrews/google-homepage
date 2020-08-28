# google-homepage
I made a google

It certainly took quite a while, but the project definitly does look like the google homepage... but only when loaded in google chrome and fully expanded. Here are the things that don't behave consistently as desired.

1) The magnifying glass and microphone that go inside the search bar don't stay where intended when resizing the page. 
    I know this is due to the way I placed them. I placed them using a relative position with a left px value until they appeared where I wanted them. It looked fine on multiple browsers (Chrome and Safari) but I suspect it would look wrong on any different computer monitor. And it completely looses its placement when resizing the page horizonitally. 
2) The "search" and "lucky" buttons also don't stay where intended when resizing
    This is the exact same issue as above but it's worth noting that I thought I could resolve this by justifying the left button to the right of a 1fr grid box and the lucky button to the left of a second 1fr grid box and spacing a grid gap or some padding in between to acheive the desired spaceing. The problem was  that never got that far because I couldn't seem to justify the search button to the right. I went back to relative position so they'd at least look good on my particular viewing screen. 
3) The background color of the search and lucky buttons didn't stay the same when loaded on Safari even though they looked good on Chrome.

I may have over done the complexity of my project as I ignored the process of using the <ul> tag for the header and footer and instead created a grid. This could also have an effect on the placement issues above, particularly with the buttons. At least I learned a lot about creating and manipulating grids! I also may have done more work than some on insrting and formating the behavior of links to match google's homepage so I guess all an all a success. As I write this I can't help but wonder if I'll ever read this or if anyone else will. If you're reading this some solutions on the above problems would be greatly appreciated. 