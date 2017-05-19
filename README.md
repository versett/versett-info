#Versett Info
Common things to know about Versett in one package.

## Installation



    npm install versett-info


## Usage

`versett-info` contains a few key pieces of data to centralize our most commonly referenced information:

### `.ContactInfo` Object
Main contact info. Contains the following keys:

- `phone`: our main phone contact line
- `email`: our main contact email
- `website`: our website url

### `.Social` Object
Our social profiles. Contains the following keys:

- `twitter`: Twitter URL
- `instagram`: Instagram URL
- `dribble`: Dribbble URL
- `medium`: Medium URL

### `.ASCII` String[]
Line by line array of a simple V// ASCII art! Looking for pull requests to improve!

### `.Locations` Object[]
Our main office locations for easy reference. Each array item contains the following keys:

- `name`: Location name
- `code`: Airport code
- `address`: Address line
- `city`: City
- `region`: Region ( Province, State )
- `postalCode`: Postal / Zip Code
- `country`: Country
- `googleMaps`: URL to Google Maps location


### `.People` Object[]
Some VIPs in the V//. Each array item contains the following keys:

- `name`: Name
- `title`: Title
- `website`: Personal Website
- `twitter`: Twitter Handle ( without @ )

### `.News` Object[]
Some links to some of the latest happenings. Eventually this will be a link to a feed! Each array item contains the following:

- `title`: A title for the news item
- `description`: A longer form description of the news item
- `url`: URL to the news


## Support & Ownership

This package is actively supported by the [Versett](http://versett.com/) team.
