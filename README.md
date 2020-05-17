# Assessment for ID 19 Responsive Design

This is a Product Landingpage for the Project Mitchell and I will be working on over the summer.
We don't plan to publish it actually, it's more a personal project for us. That's why I didn't spend time actually writing the text for it, rather looking at the different content types someone might want to have to advertise the product.

I wouldn't say that I focused on any part of it, as I had no experience with both. I first wanted to focus on Tech, but then found some joy in the designing part and got a little bit lost in visuals. For Tech I already assumed that I will run into some problems as my last (and very short) contact with html and css was 10 years ago.

##Design Process
You can find the Designs in [my figma file](https://www.figma.com/file/UWbOTAHzDoVR936ML4Hyxz/Selma?node-id=124%3A18).

To say in the beginning: Apart from my little experience with Design in the Orientation Semester, I haven't touched any Design work until this project.

In the beginning of this project I looked into a wireframing kit of Figma, but because I never really used Figma, it was very overwhelming to work with the styles and components, without knowing where it comes from and what is happening.
I dumped the wireframing kit and started from scratch, focusing on how I want my website to look.

As the content of the website is quite minimalistic, the contect can be displayed in a 1, 2 and partly a 3 column grid. For mobile it just changes to a 1 column grid.


##Dev Process:
Problem of Development process and style guides, I wasn't very aware of how much you can speed up the dev process with good naming and defined styles in the design file.

Talking to different people, it's quite funny how it's divided between Flexbox and Grid. I used both now, as I wanted to try out how it works. Probably not very clean yet, and far from best practise, but it was interesting to play around with it. The more I'm looking now into it, the more I realize that practise will speed up the process significantly.

The navigation was harder than I planned it will be, mainly because the blobs in the background have a difficult corelation with the max width. Also the 500 different tutorials on how to implement a navigation don't really help.


##Problems with the Design and Responsiveness:
At times I cursed my very graphical screen design, because it was way too difficult for my very limited CSS skills. But changing the Designs to match the programmin skills is also more than frustrating.
In my first final design, I had these background graphics/blobs. It was planned that they would strech over the display, no matter how big it is. Especially for these overly wide screens, I set the view to 1200px, so people don't feel like they are on a tennis court. This was the only hardcoded px area, that made it impossible to use the blobs the way I designed it.
What I imagine could work, are purely css animated backgrounds, that strech over the screen, but in the given time I found no solution for SVGs and decided to iterate on the Design.

Timewise I had to stop while optimzing the implementation of the mobile screen. At the moment the background svgs are interfering with the screen width and prevent me from adding padding. The padding that I would add for the "wrapper" divs is adding to the max-width for the background images. As I will continue working on the page, I will probably solve it differntly, with :before.

Next steps for me are including taking the Web Tech Module in Summer, so I will interate over the implementation, clean up the unneccessary classes and id and rework the background.
