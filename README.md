# sg-fire
Number or rate of fires (accidental / deliberate)

This dataset provide the numbers and rates of fires in Scotland down to datazone level. Data is provided for the total number of fires, including accidental and deliberate causes.

Data is entered by the Scottish Fire and Rescue Service into the Incident Recording System.

Dataset taken from http://statistics.gov.scot/data/fire

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/sg-fire.git
```

Install npm dependencies

```
cd sg-fire
npm install
```

Run the API (from the sg-fire directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
