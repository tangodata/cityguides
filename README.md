# cityguides

List of local city resources by Crowd-Sources

- Each city has one YAML file 
   - filename is (iata-code)-(cityname)-(country).yml
   - directory is  cities/(continent)
   - iata-code is the principal airport 3-letter code
     (look up http://www.nationsonline.org/oneworld/IATA_Codes/airport_code_list.htm)
   - a city can also include data of its metropolitan neighbours 
   
- YAML file has to follow the layout of the SKELETON
   - data on regular programs
   - data on regular venues
   - data on main newsfeed/ groups
   - data on the city for visitors
   - data on main  weblinks
   - data on festivals and annual programs
   
- YAML file includes pointers to volatile data (those that changes weekly)
   - RSS to a source of newsfeed (or sources)
   - GCAL to a calendar feed (or feeds)
   - pages for transclusion (about, what's hot etc)
   
- After a city has been coded into a YAML, it is not published until
   1. it is checked for format compliance
   2. at least one local contact person is recorded
   3. at least one month of volatile data is verified
   
- The published data goes into /data

#### Mods and Corrections

As this repo is open data, it is up to each contributor to make
changes.  It is up to each application to refresh their source
data.
