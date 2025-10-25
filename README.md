// Using var, let, and const
var name = "Ayas";          // string data type
let age = 21;               // number data type
const isFresher = true;     // boolean data type

// Reassign values (var and let allowed)
name = "Mohamed Ayas";
age = 22;

// const cannot be reassigned -> this would throw error
// isFresher = false;

// Different Data Types
let city = "Chennai";             // String
let salary = 25000.50;            // Number (float)
let hasJob = false;               // Boolean
let skills = ["HTML", "CSS", "JS"]; // Array
let profile = {                   // Object
  degree: "B.Com",
  experience: "Fresher"
};

// Basic Operations
let addition = age + 5;
let subtraction = salary - 5000;
let multiplication = 10 * 2;
let division = salary / 2;
let modulus = 10 % 3;

// Output results
console.log("Name:", name);
console.log("Age after 5 years:", addition);
console.log("Remaining Salary:", subtraction);
console.log("Multiplication:", multiplication);
console.log("Division:", division);
console.log("Modulus:", modulus);
console.log("Skills:", skills);
console.log("Profile:", profile);
