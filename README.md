Hi, I made this landing page with Bootstrap 5. I followed the template design, and it works on mobile, tablet and desktop. I used Bootstrap's grid and ready-made classes as much as I could. I wrote my own CSS only when Bootstrap couldn't do the design, like the slanted sections, the cards and the sliders. I used JavaScript in only three places: the logo slider, the testimonial slider and the portfolio filter."

If asked, "How is it responsive?"
"I used Bootstrap columns like col-12 col-md-6 col-lg-3. So mobile shows 1 column, tablet shows 2, and desktop shows 4. I also added the viewport meta tag, so it fits properly on phones."

Section by section

1. Navbar
"This is the normal Bootstrap navbar. On mobile the menu becomes a hamburger button, and the Get Started button is still visible. The dropdown is also from Bootstrap, so I didn't write any JavaScript for it."

2. Hero section
"The background is an image with a dark layer on top, so the white text is easy to read. I used min-height: 87vh and not a fixed height, so it doesn't break on small screens. The Watch Video link turns red when you hover."

3. Client logos slider
"I made this slider myself. All logos are in one row, and when you click a dot, the row moves left. It shows 2 logos on mobile, 4 on tablet and 6 on desktop. Logos are grey and get colour on hover. I repeat the logos once in JavaScript, so the last dots don't show empty space."

4. Features section (dark, slanted)
"The slanted top and bottom are made with clip-path. I used pixel values for the slant, so it looks the same on tall phone screens and doesn't cut the content. The icons are SVG, so I didn't need any icon library."

5. Stats section (232, 521, ...)
"These are white cards with a shadow. The round icon sits half outside the card. I did that with position: absolute and transform. The cards show in 1, 2 or 4 columns, depending on the screen."

6. Tabs section
"This is Bootstrap pill tabs, so no custom JavaScript. Each button connects to its content with data-bs-target. The active tab is red, which I did in CSS. On mobile the buttons stack, and the image comes below the text."

7. Services section
"Dark slanted background again, with 6 cards in 2 columns. On mobile it becomes 1 column. In each card, the icon is on the left and the text is on the right, using d-flex."

8. Portfolio section
"There are 12 images and filters: All, App, Product, Branding and Books. Each image has a data-category. When you click a filter, JavaScript hides the other images with Bootstrap's d-none class. I used ratio and object-fit: cover, so all images stay the same size."

9. Testimonials section
"This works like the logo slider. It shows 3 cards on desktop, 2 on tablet and 1 on mobile. It moves by itself every 3 seconds, one card at a time, and clicking a dot also moves it. I put the script inside a function, so the variable names don't clash with the logo slider."

10. Pricing section
"There are three plan cards. The middle one is red and taller, so it stands out. On mobile all three are the same size and stack one below the other. The ticks and crosses are just text characters, so no icons are needed."

11. FAQ section
"This is the Bootstrap accordion, so no JavaScript again. Only one answer stays open at a time because of data-bs-parent. I used CSS to make the open item have a red title and a light red background, like the template."

12. Team section
"Four member cards in a dark slanted section. All photos are square using aspect-ratio, so even if the original images are different sizes, the layout still looks neat."

13. Contact section
"On the left there are cards for address, phone and email. On the right is the form. On mobile the form comes below the cards. The icon circles have a dotted red border. The form uses Bootstrap's form-control, and I added required for basic validation."

14. Footer
"The footer has 4 columns on desktop, 2 on tablet and 1 on mobile. It has social icons, link lists, a newsletter box and the copyright line. The icons are SVG, and the links turn red on hover."
