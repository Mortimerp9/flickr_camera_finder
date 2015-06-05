This scraper liberates the data from Flickr Camera Finder (http://www.flickr.com/cameras/), extracting a list of:
* Camera brands
* Camera models for each brands
* numbers of users on Flickr when  the camera model was first crawled.

The scraper also extracts "yesterday" stats for each camera:
* number of users that uploaded photos yesterday
* number of photos that were uploaded yesterday
so that the evolution of the cameras can be plotted. Note that this doesn't do anything smart about the date as it stores the date of the crawl.

You can view the results of this crawling here:
* "Camera Maker statistics":https://views.scraperwiki.com/run/brand_distribution/

Please keep in mind the following note by Flickr:
“The graphs are only accurate to the extent that we can automatically detect the camera used to take the photo or shoot the video (about 2/3rds of the time). That is not usually possible with cameraphones, therefore they are under-represented.”

Anyone is welcomed to contribute, just ask me.

Scraping history
---------

- ran on scraperwiki from 2011-10-01 to 2013-04-07 almost daily.
- big hiatus when scraperwiki updated their API and went read-only.
- running since 2015-06-04 on [morph.io](morph.io/Mortimerp9/flickr_camera_finder) mostly daily.

You can find the data as an sqlite db or a csv file at https://morph.io/Mortimerp9/flickr_camera_finder
