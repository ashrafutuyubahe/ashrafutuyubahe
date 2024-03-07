# Distance Calculator

Calculate the distance between two geographical coordinates using this simple package.

## Installation

You can install this package via npm:
=>npm install ashraf_distancecalculation_tool

### Usage of this package 
distanceCalculator = require('ashraf_distancecalculation_tool')

// Example usage

const distance = distanceCalculator.calculateDistance(40.7128, -74.0060, 34.0522, -118.2437);
console.log('Distance:', distance, 'km');



 ## full documentation of API

calculateDistance(lat1, lon1, lat2, lon2)
Calculates the distance between two geographical coordinates in kilometers using the Haversine formula.

.`lat1`: Latitude of the first point.
.`lon1`: Longitude of the first point.
.`lat2`: Latitude of the second point.
.`lon2`: Longitude of the second point.
.Returns the distance in kilometers.


##  Contributing
Contributions are welcome! If you have any ideas, enhancements, or find any issues, please open an issue or submit a pull request.

## License
`This package is open source and available under the MIT License.`



