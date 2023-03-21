# task-3 
For loop

let obj = {
  "name": "John",
  "age": 30,
  "email": "john@example.com",
  "hobbies": ["reading", "painting", "traveling"]
};

for(let i = 0; i < obj.hobbies.length; i++) {
  console.log(obj.hobbies[i]);
}



FOR in...loop
let obj = {
  "name": "John",
  "age": 30,
  "email": "john@example.com",
  "hobbies": ["reading", "painting", "traveling"]
};

for(let key in obj) {
  console.log(key + ": " + obj[key]);
}

For of loop

let obj = {
  "name": "John",
  "age": 30,
  "email": "john@example.com",
  "hobbies": ["reading", "painting", "traveling"]
};

for(let hobby of obj.hobbies) {
  console.log(hobby);
}

for each loop

let obj = {
  "name": "John",
  "age": 30,
  "email": "john@example.com",
  "hobbies": ["reading", "painting", "traveling"]
};

obj.hobbies.forEach(function(hobby) {
  console.log(hobby);
});








read about the different between window,screen and document in javascript

The window object represents the entire browser window or tab. It is the top-level object in the browser's hierarchy of objects and contains properties and methods related to the current window or tab. Some of the common properties and methods of the window object include location, document, setTimeout(), setInterval(), and alert().


The screen object represents the physical display screen of the user's device. It contains properties and methods related to the display screen, such as width, height, colorDepth, and availWidth.



The document object represents the HTML document that is currently being displayed in the browser window. It contains properties and methods related to the document, such as getElementById(), createElement(), addEventListener(), and innerHTML.




Create your own resume data in json format
{
    "name": "Devapandian",
    "age": 26,
    "city": "paramakudi",
    "email": "Deva@example.com",
    "phone": "9790336666",
    "interests": [
        "travel",
        "photography",
        "reading"
    ],
    "education": {
        "degree": "Bachelor of engineering",
        "major": "Electronic and communication",
        "school": "Anna University",
        "graduation_year": 2018
    }
}

