# data-entry-assist
a web utility for quickly classifying rows of data into configurable categories

## Usage

### Steps/Instructions

1. Upload your data in `.csv` format
2. Set up the variable/s you wish to classify
3. Map these variables to corresponding keys
4. Use the key mapping to quickly classify each item independently
5. Watch the progress bar to see how many you have left.
6. Download a new `.csv` file with the 

### Expected use cases
- **data mining**: building "oracles" (word of truth datasets) of manually classified data 
- **basic data entry**: adding values from a _small_ set of possibilities to a given set of values
- ...

## Features 

### Planned/Implemented
- [ ] able to upload csv datasets
- [ ] map data bindings to set keys
- [ ] able to name the project/space
- [ ] effectively store entered classifications (local storage)
- [ ] able to re-download the csv file with the created classifications
- [ ] perpetuate these bindings between sessions
- [ ] progress bar at the top of the page

### Future Ideas
- specify/customize key mappings of your own 
- establish rule sets 
- provide backend logic for multiple people to work on the same dataset on their own url (a la [when2meet](http://when2meet.com/))
  - ensure that there aren't any duplicates
  - provide ability to ensure that there _are_ duplicates and manage collisions/disagreements
  
## Technology

ideal: use the web primitives (no framework)
- vanilla js
- utilize html local storage
- css grid

## Targeted Learnings
- extent of web primitive capacities
- session management/control
- css grid 
