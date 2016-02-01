# BeeRoom
![why???](http://25.media.tumblr.com/tumblr_lzdjy2aDiu1r2pxgdo1_400.gif)

### Beepi, Vroom, etc. in one place

A library for searching all the new places to buy a used car online. This is useful because the online-used-car-buying market is so fragmented, you have to interface with 7 different search engines, which is absurd.

![nobody](http://i.giphy.com/bWM2eWYfN3r20.gif)

Also I want to practice using every silly future-ES tool, Rx.js, etc.

### Status
This is a total WIP. Currently, inventory can be pulled from Beepi and Vroom by manually setting body style and price. The script has to be run from the command line. The goal is to use Rollup.js or Browserify to include this in a web page. Then the scraping does not come from one server, but by the actual car buyer, which raises the question: is it scraping at all?

### Timeline

Calling this a timeline is absurd, but here is a reasonable ordering of tasks that need to be completed for this project to work.

1. Add interface for specifying options
  - Currently, the only options are price and bodystyle, and maybe mileage. This could be expanded eventually
  - Eventually want to add sources more than Beepi and Vroom
2. Create a front end
  - May as well use React and anything else that's hip
3. Browserify backend code to be used on the client
  - Why not just keep the code on the backend? Then that backend is scraping the sites, which is questionably legal, and you have to deal with rotating the IP, etc
4. Host on GH pages or some other static file host, since it will be only HTML, CSS, and JS.
5. Profit?

### Contributing

PLEASE HELP ME!
