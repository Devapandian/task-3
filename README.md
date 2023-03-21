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
