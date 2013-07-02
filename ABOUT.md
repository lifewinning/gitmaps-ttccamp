Why Do This? Who Is This For?
-----------------------------

This tutorial is for people who want to see some data they've collected on a map with minimal styling, learn more about using GitHub, and learn more about web mapping and coding. 

**tl;dr section begins....now!**

####What about Google?

Look, I'd be kind of a jerk if I didn't tell you that [Google Fusion Tables](https://support.google.com/fusiontables/answer/2571232?hl=en) exists. If you're trying to do slightly more complex visualizations without having to do any coding, or if you need a point-and-click backend to your map, I'd recommend checking out that documentation instead and giving those tools a try. 

####Why I'm telling you that but also going to try and convince you to stay here

I have trouble purely dismissing Google mapping tools entirely when trying to teach others about maps. This is partly because of my own experience (I learned the Google Maps API first, and learning that helped me get comfortable using other tools). It also seems hypocritical to recommend using a Google Spreadsheet-based plugin and then be like, "No, no, don't use Google Maps." 

But, as long as I have your attention, here is a breakdown of who might benefit from stepping away from the Googleplex and why.  

+   **How much backend do you really need?** This is more of an argument about redundancy. Google Fusion Tables is great if you've got a whole bunch of things you want to do with your data and you're going to maintain it. If you literally *just want to see it* and you're not storing it, this demo repository might be helpful.
+   **Sharing is fun.** When you store map data in a Google Fusion Table, it is totally feasible to do some digging in your code and find the original data table. Depending on your settings, people can then just download your data from there. But GitHub requires a lot less effort to make that data available to other people who might want to tinker with it. So even if you're not a data visualization expert, maybe someone else who is can fork your repository and do something cool with it!
+   **Learning things is neat!** Or, I think so anyway. 
+   **Aesthetics matter.** It's kind of a superficial point, but Google Maps just isn't as pretty as OpenStreetMap. The markers aren't as nice, the popups aren't as nice. And while you can modify the style of a Google base map, I still just think Leaflet and Mapbox are more flexible in accomodating your design choices. If you want to get into geo visualization followng this tutorial, I really think you'll be happier with the results if you don't work with Google. All the cool data visualization kids are using it.  
+   **The more people use OpenStreetMap, the better it gets.** If this repository was helpful and you want to find out more, do it! If you want more things to be on OpenStreetMap, join the community and add things!
+   **Longer-term: what kind of data are you working with, and do you feel OK with Google having it?** This repository isn't necessarily a solution for making super-private maps, but if that's something you're interested in, start by learning this stuff. Google's not going to build you a solution for escaping Google. 

This is kind of getting ahead of ourselves--you wanted to make a map, not get a lecture about open source! This is what blogs are for. Check out the rest of the documentation and examples, and let's actually make a thing.
