#Digital Mapping Tool Tutorial

Digital mapping is a great tool with potential to change the ways we encounter textual spaces. I think there is great value to be found in transforming the worlds we encounter in texts into visualizations. What opportunities for interpretation and connection can be opened by changing the ways in which we encounter these spaces? Digital mapping is useful when analyzing both the movements of a character/feeling (or anything else which can be tracked in such a way), or the changes a landscape experiences over time. 

Furthermore, the ability to transform and manipulate a historical map has potential for changing the ways we approach scholarship of the past. What violences can be acknowledged and addressed by using historical maps to shape the ways we interact with the past and the people who traversed those physical and political landscapes?  

In this tool tutorial, I will focus on one specific possibility for using digital mapping to interpret literature. I will introduce you to two stages in transforming a map to display the movements of characters and events in a novel. Though this is a fairly simple method of analysis, my hope is that the introductory techniques will show the readers how digital mapping can be useful and feasible to accomplish. 





#Tool Tutorial 

This tutorial will work you through the steps to georectifying a historical map using an online program called Mapwarper. This will fit the map onto a modern day Google Maps. The second step will be through a program called Palladio, and will let us impose points on the historical map. The example I’ve chosen is to chart the movements of David in Charles Dickens’s *David Copperfield*. As you’ll see in my other tutorials, I love working with this text when experimenting with DH tools because it is rich with details and also malleable. 

![David and Dora](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/davidcopperfield.png?raw=true)

##Finding the data 

The map I’ve chosen for our tutorial today is from the People’s Atlas and was made in 1920. If you’re following along, you can download the map [here](http://www.hipkiss.org/data/maps/london-geographical-institute_the-peoples-atlas_1920_england-and-wales_3012_3992_600.jpg). Otherwise, you are welcome to use a map that fits your interests. I will say, however, that due to the early stages of development of many of these programs, maps which cover larger spaces, such as this map of the UK, are easier to work with. 

![map of england](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/ukmap.png?raw=true)

##Mapwarper 

Next, we have to upload our map to Mapwarper. This will allow us to georectify the map - essentially, stretch it onto a Google Maps template - and allow us to manipulate it in Palladio. 

Go to [MapWarper](http://mapwarper.net/maps) and sign up for an account. Next, upload your historical map. 

![historical map](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified.png?raw=true)

Once you open up the new map, you want to click on the tab that says “Rectify.” 

Now, here is where the real work begins. First, find the UK on the map on the right. Once you’ve zoomed in appropriately, begin adding Control Points. Control Points allow us to align the two maps by adding points that are the same on each one. For example, you might want to place a control point on recognizable cities or on changes in the geography. The minimum is three, but the more the better.

This can be quite tricky and tedious, especially when dealing with territories that have changed significantly since the historical map was made. This is why I suggest trying with a larger map, especially for the first time. I’ve tried to georectify historical maps of cities and it can be tricky, especially when considering the artistic flourishes of the craftsmen. 

In order to drop a pin, click on the symbol in the upper right corner of the first map, which looks like a pencil with a + symbol. 

When working so intimately with these historical maps, it is very interesting to think about how cultural landscapes shape the way we think about geographical landscapes. For example, what does it mean about Eurocentrism that such detailed, meticulous maps of England exist? The one I’m working with here, for example, is really very accurate in terms of geography and features individual villages and towns. This is a landscape which has been depicted and cultivated over hundreds of years. Why might certain regions be more accurate than others? An interesting project for another time would be to look at historical maps of countries which were colonized and how the cartography changed and developed during the stages of colonization. What does it mean for us to look so intimately and critically at maps in such a way? 

But I digress. 

When you’re done and feel confident about your control points, select “Warp Image!” at the bottom of the page. This will superimpose your historical map onto the Google Maps window. If you’re interested, you can move the slider at the bottom to admire how the landscape of the country changes. 

![warping image](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified-2.png?raw=true)

To export your map, click the “Export” tab at the top. We want to keep the Tiles (Google/OSM scheme), which we will use in Palladio. Make sure you save the link! 

Here is my link for the map I’m working on: 
http://mapwarper.net/maps/tile/13534/{z}/{x}/{y}.png

You are welcome to use this link if you want to skip ahead to the Palladio portion of this tutorial. 

Great work! 

##Palladio 

The next step is to go to Palladio, which is a tool designed by Stanford for map visualizations. Palladio can be quite hard to use, since it’s still a pretty new program, and I’ve had a lot of problems with it. Despite this, I do think it is worth experimenting with and that the tools you can use it with do have the potential to yield interesting results. 

[Palladio](http://palladio.designhumanities.org/#/)

Press “Start.” 

Palladio will ask you to input some data for your map. Since we’re doing a visualization of David’s movements in *David Copperfield*, I’ve gone ahead and gotten the latitude-longitude coordinates for the four main settings of the novel. Just copy-paste the data below (including the titles “City” and “Coordinates” into the space for data on Palladio. 

###Data for Palladio

If you’re re-creating the project I’m working on, then you can just copy-paste the data table below. **Note: Because of the formatting of this publishing platform, it might be necessary to copy-paste these into columns on Excel, and then copy-paste that formatting into Palladio. This is mostly due to the fickleness of Palladio.**

City 	Departure	ArrivalBlunderstone	52.4811,1.7534	52.5982,1.728Yarmouth	52.5982,1.728	51.32,0.0759London	51.32,0.0759	51.2802,1.0789Canterbury	51.2802,1.0789	51.1279,1.3134Dover	51.1279,1.3134	51.1279,1.3134


Now that you’ve put in the data, we need to make sure it’s appropriately categorized. In the next screen, click the edit button - the little pencil - next to “Coordinates.” Under “Data type” change the type to “Coordinates.”

![coordinates](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified-1%20copy.png?raw=true)

Click on the tab that says “Map” at the top of the window. This will show you a white and grey map of the world in the background, with a window which will allow us to add and edit new layers. Select “New Layer.” The first layer we need is to integrate our data. As you can see in the image below, I’ve filled out the fields so that the points will be connected, setting up “Source Places” and “Target Places” accordingly. Also, make sure to select the “Map type” as “Point to Point.” When this information is prepared, then click “Apply.”


You’ll be able to see that the points and lines have been added to the background land map. 

![background](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/dotson.png?raw=true)

Next, we need to input the historical map that we georectified using MapWarper. Once again, select “add a new layer.” Then go to the tab that says “Tiles.” Select “custom.” In the space where it says “Tileset URL” we want to put in the link we got from MapWarper (for the map I’m editing here, it is: 

http://mapwarper.net/maps/tile/13534/{z}/{x}/{y}.png

Once this is done, hit “Apply.” We should now have a beautiful historical map imposed over the UK. You can zoom in and out on the UK to see how it fits in with the landscape. Furthermore, we can see the dots on the various places where David goes in the novel *David Copperfield.*

![ex 1](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified-5.png?raw=true)

![ex 2](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified-1.png?raw=true)

![ex 3](https://github.com/jennaherdman/gitbookdh/blob/master/images%20for%20digital%20mapping/unspecified-6.png?raw=true)

Well done! 

##Exporting your map 

Unfortunately, the current version of Palladio doesn’t allow you to export your map. I’ve just been taking screenshots to retain my maps for other purposes. If you’re planning to keep editing, you can save your work by selecting the “Download” button in the top right corner and upload the file at a later date.  

##Conclusions

This tutorial has walked you through the basics of MapWarper and Palladio. There are tons of opportunities to experiment with these tools as you become more familiar with the kinks of the two websites. If you’re a beginner in these tools, I’d suggest running through this tutorial with a few different maps to suit your research purposes or interests. The links below show several other projects using these tools which I would highly recommend checking out. I’ll conclude this tool tutorial with a few examples of nineteenth century lit DH projects that I’d love to see done, or perhaps accomplish myself in the future. 

* Daniel Defoe’s London in *A Journal of the Plague Year*
* settings and movements of different Dickens novels 
* mapping sites of “feeling” or “sympathy” in literary England 

#Further Information

[Miriam Posner’s tool tutorial](http://miriamposner.com/blog/getting-started-with-palladio/)

[John Levin’s blog](http://anterotesis.com/wordpress/2011/03/digital-humanities-gis-projects/)

Project by the centre for Spatial and Textual Analysis at Stanford University. The project has several different elements, but I have linked to one which shows [the evolution of the SS concentration camp system from 1933-1945](http://web.stanford.edu/group/spatialhistory/cgi-bin/site/viz.php?id=379&project_id=0)

