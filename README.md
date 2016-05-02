# is-json
simple utility to function to test if a string is valid JSON or not

        var isJSON = require('is-json');
        
        console.log(isJSON('{}')); // => true
        console.log(isJSON('{I am not a valid JSON}')); // => false
