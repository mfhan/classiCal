
# ClassiCal

## Helping You Pick Your Next Classical Concert

You love music, all kinds of music, and love going to concerts! Except for classical music. Have you looked at a Carnegie Hall program? Or a Lincoln Center calendar? So many composers, so many pieces, so many interpreters! 
The biggest barrier is that it's nearly impossible to figure out what a piece sounds like from just reading a program. 
ClassiCal is a site that scrapes (several) classical music sites and ADDS LINKS to YouTube videos corresponding to the pieces to be performed. It's a one-stop shop to check out what's coming up and discover what it sounds like in order to help you decide
!

### Project Links
- github: [https://github.com/mfhan/classiCal](https://github.com/mfhan/classiCal)
- [deployment: TBD]
- [Medium article on my tribulations] 


### Technical value: 
I want to practice 1. dynamic web scraping and 2. dynamic rendering of content.
-- Exploring Puppeteer.js / Cheerio.js and other HEADLESS SCRAPING TOOLS
-- Web Scraping is a great way to re-familirarize myself with HTML/CSS syntax
-- Using REACT for rendering 

#### TOOLS: 

-- React Hooks  
-- Node + Express
-- Puppeteer
-- PostgresQL/MongoDB 
  


### Two-week Sprint Plan: 

#### Week 1a: Scraping 
-- Scraping for ONE element
-- Scraping in loops to render content of an entire site
-- Scraping several sites and rendering

#### Week 1b: Video-Searching
-- Studying protocol for finding RIGHTS-FREE videos

#### Week 2a: Rendering

#### Week 2b: OPTIMIZING youtube video selection


### Overcoming Blockers

#### Blocker 1: Frustration regarding JavaScript scrapers 
JavaCcript scraping tools are just coming of age and most of them have runtime and efficiency issues, especially compared with Python. 

#### Blocker 2: 

#### Blocker 3: 





### MVP/PostMVP

#### MVP:
--   

#### PostMVP:

-- Allow user to select a DAY and TIME SLOT for her availability  
-- Allow user to SELECT potential coworking matches via filter   
--  Use YELP or FOURSQUARE APIs to render cafes on map  


## Wireframes


### App Home:  
 <img src="https://docs.google.com/drawings/d/e/2PACX-1vSKruZ0yIwUlwq-N6ehmdvsPyDMxYUsDaHLUZzzDtzQmU09BpqWUa1Z1RK3YUMk2o2PO3_MV2TU01TO/pub?w=2193&amp;h=1072">

### Log-In/Register Page:   

<img src="https://docs.google.com/drawings/d/e/2PACX-1vRN46Fym2QuLqUSDUl5KcGAjjPZ2HP7uil3a-6Zxu5TLPwqqyKvUwXRx_la-mL8ijjMtgNtjQQHSvNo/pub?w=2193&amp;h=1072">

### Post-Log-In View  
<img src="https://docs.google.com/drawings/d/e/2PACX-1vS4IUNfx6VdjW4nViof93nUePWAuSLVaJoxAD6gYfjd6uIVc2USXoMqLLFMsE9zZb8CCb1lrr7hrKeD/pub?w=2193&amp;h=1072">

## API

-- Mapbox API + Uber's ReactMapGL public repo for functionalities

-- Code sample:
```js
<ReactMapGL
            {...this.state.viewport}
            mapboxApiAccessToken = {process.env.REACT_APP_MAPBOX_TOKEN}
            mapStyle = 'mapbox://styles/parisny/ck0lefyty5kux1cte8t6fukb6'
            onViewportChange = {(viewport) => this.updateViewport(viewport)}
            onClick = {this.props.mapClick}
          >
            ///MAP will pass other users' locations with a pin, a marker, a radius circle, and a pop-up infowindow
        </ ReactMapGL>
```


## React Components:  

<img src="https://docs.google.com/drawings/d/e/2PACX-1vQ04yzGGwuLjqxaoj_jRH7PODuxBr_NGYJnDwBuii68jeG78ZUxKm1sLDHw9tWYWrBrHBDai3B7_jmD/pub?w=1440&amp;h=1080">


## Components


| Component | Description |
| --- | :---: |  
| App | will handle user creation and updates; render the Map; act as Router|
| PersonalDataForm | Will allow user to create/update her account and click on her desired coworking locations |
| MatchList (FILTER)| Will render possible coworking matches in list form |  
| Map | Will render a populated map|  
| Header | This will render the header which houses the log-in functionality |
| Footer | This will render the footer |

## Time Frame  

| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Working with REACT MAP GL API | H | 8hrs| -- | 10hrs |
| Adding radius logic to MAP  | HH | 4hrs| -- | -- | SCRAPPED
| Working with date filter logic  | H | 4hrs| -- | 12hrs |
| Header with log-in | M | 6hrs | --   | --  | -- |
| Home page styling | H  | 6hrs | --   | --  | -- |
| Total | H | -- | -- | -- |

## Additional Libraries




 
