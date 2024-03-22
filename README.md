# Daily Pennsylvanian Headline Scraper

Based on the basic scraper template. Changed the scraping function to be more sports oriented--the scraper looks at each sport listed in the "sports" section of the DP
and grabs the most recent headline from each sport, compiling the data into a python dictionary. The headline is found by selecting the class name and the associated text which
is the same structure for each sport. This text is combined with the sports name and represented as a dictionary mapping the sport to its headline. 
