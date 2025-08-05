a:age >= 18 && genAverage >= 83
? console.log("You may enter College, under BSCS Program")
: console.log("Both conditions may have not met and not allowed to enroll");
subject === "DSA" && grade >= 80
? console.log("You may enroll Application Development")
b : subject === "Math101" && grade <= 80
? console.log("You may enroll Calculus")
: console.log("You have to enroll DSA and pass to enroll AD and Math101 and pass to enroll Calculus");
1.2:if (age >= 18) {
console.log("You may Now Register as a Voter for Elections 2025");
} else {
console.log("You are too young register as a voter for Elections 2025");
}
1.3:let fName = "Jose Cruz";
for(i = 0; i < fName.length; i++){
let c = 2 + i;
let lengthCounterTwo = fName.length - c;
console.log(fName);
console.log("Iterations Name was Printed: " + i);
}
II:let regCode = prompt("Register your Username:");
let regPass = prompt("Register your passcode:");
let rePass = prompt("Re-enter your passcode:");

if (regPass === rePass) {
let loginCode = prompt("Username:");
if (loginCode === regCode) {
let loginPass = prompt("Password:");
if (loginPass === regPass) {
alert("Welcome to DSA, " + loginCode);
} else {
alert("Incorrect Password, Re-run the code!");
}
} else {
alert("Incorrect Username, Re-run the code!");
}
} else {
alert("Password does not Match, Re-run the code!");
}
|||:let name = prompt("Enter your name:");
let address = prompt("Enter your address:");
let age = parseInt(prompt("Enter your age:"));
let role = prompt("Enter your role (Officer, Student, Teacher):");
let course = prompt("Enter your course (BSCS, BSM, BAEL):");

if (course === "BSCS") {
if (role === "Student") {
let loops = Math.floor(age / 4);
for (let i = 0; i < loops; i++) {
console.log(name + " - BSCS Student");
}
}
// Add similar blocks for Officer, Teacher
} else if (course === "BSM") {
// Similar nested condition
} else if (course === "BAEL") {
// Similar nested condition
} else {
console.log("Invalid Course");
}
