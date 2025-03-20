function removeSpecialCharacters(str) {
    return str.replace(/[^a-zA-Z0-9 ]/g, ''); // Keeps only letters, numbers, and spaces
}

const input = "Hello-.*+?^${}()|[]\\World@#&!%";
const output = removeSpecialCharacters(input);
console.log(output); // "Hello World"