# cinema-finder-poc
Created with CodeSandbox


### Hey! I am Kelvin, the taker of this course
    I worked on the issue where clicking the markers on the cinema listings didn't do anything. 
    The reason was because MapLibre's flyTo functions had the arguments switched around (Was supposed to be [lon,lat] but ended up [lat,lon])
    That should work now!