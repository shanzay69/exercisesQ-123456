# exercisesQ-123456
This repository contains basic TypeScript exercises that cover fundamental string manipulations, including greetings, case conversion, and whitespace handling.

Q2: Personalized Greeting
A simple TypeScript program that greets a person with their name.
typescript
Copy
Edit
let personname = "shanza";
console.log('Hello', personname, "would you like to learn some TypeScript today?");
Q3: Name Formatting
Converts a given name to:

Lowercase
Uppercase
Titlecase
typescript
Copy
Edit
let personname = "shanza";
console.log(personname.toLowerCase());  // shanza
console.log(personname.toUpperCase());  // SHANZA
console.log(personname.charAt(0).toUpperCase() + personname.slice(1).toLowerCase());  // Shanza
Q4: Famous Quote
Prints a famous quote by Allama Iqbal.

typescript
Copy
Edit
console.log("Allama Iqbal once said", '"Islam is itself destiny and will not suffer destiny"');
Q5: Famous Quote with Variable
Stores a famous person's name and their quote in variables, then prints them together.

typescript
Copy
Edit
let famousperson = "Allama Iqbal";
let message = "one said, 'Islam is itself destiny and will not suffer destiny'";
console.log(famousperson, message);
Q6: Whitespace Handling
Demonstrates how to handle leading and trailing whitespace using trim().

typescript
Copy
Edit
let whitespace = "\n\t shanza khan\t\n";
console.log(whitespace);  // Shows whitespace before and after the name

let withoutwhitespace = whitespace.trim();
console.log(withoutwhitespace);  // Removes whitespace
How to Run the Code
Install Node.js if not already installed.

Save the code in a TypeScript file (e.g., index.ts).

Compile the TypeScript file using:

Copy
Edit
tsc index.ts
Run the JavaScript output file:

Copy
Edit
node index.js
