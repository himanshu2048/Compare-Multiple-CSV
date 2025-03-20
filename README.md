function removeRegexCharacters(str) {
    return str.replace(/[.*+?^${}()|[\]\\-]/g, '');
}

const input = "Hello-.*+?^${}()|[]\\World";
const output = removeRegexCharacters(input);
console.log(output); // "HelloWorld"