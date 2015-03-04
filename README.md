# What is this? 
This is a map of child care centers in Somerville, MA. Its purpose is to enhance the [Somerville Early Childhood Hub](http://somervillehub.org/), a place to find resources for young children & their families in Somerville. 

Here's what the app looks like in action:

![Searchable Early Childhood Map](/images/searchable-map-screenshot.png)

We heard from the wonderful staff behind the Hub that they have often talked about having a map of centers on their website, but didn't know how to create one. We built this for them during [CodeAcross 2015](http://www.meetup.com/Code-for-Boston/events/219132652/) so that they can drop in a searchable map as an iframe.

# What's the tech? 
This map was built using Derek Eder's [Fusion Table Searchable Map Template](https://github.com/derekeder/FusionTable-Map-Template). The template is free to use and very well documented on GitHub. There's also a [project page](http://derekeder.com/searchable_map_template/) with lots of neat examples of the searchable map template in action.

# Where's the data from?
The initial data behind the map comes from Code for Boston, specifically the [child-care-finder-data](https://github.com/codeforboston/child-care-finder-data) & [child-care-finder](https://github.com/codeforboston/child-care-finder) repos. Code for Boston in turn got the data from the the Mass. Dept. of Early Education & Care (see [codeforboston/child-care-finder#2](https://github.com/codeforboston/child-care-finder/issues/2#issuecomment-75475746)).

# What's the status?
As of CodeAcross weekend, this map is an experiment! The plan is to drop it into Somerville Early Childhood Hub website as an iframe, which will put it into production. 