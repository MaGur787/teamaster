# teamaster
Basic demonstration app
// Helper function to add two numbers
function add(a, b) {
  return a + b;
}

// Helper function to subtract two numbers
function subtract(a, b) {
  return a - b;
}

// Helper function to multiply two numbers
function multiply(a, b) {
  return a * b;
}

// Helper function to divide two numbers
function divide(a, b) {
  if (b !== 0) {
    return a / b;
  } else {
    return "Cannot divide by zero";
  }
}

// Example usage
const num1 = 10;
const num2 = 5;

console.log(`Addition: ${add(num1, num2)}`);
console.log(`Subtraction: ${subtract(num1, num2)}`);
console.log(`Multiplication: ${multiply(num1, num2)}`);
console.log(`Division: ${divide(num1, num2)}`);
