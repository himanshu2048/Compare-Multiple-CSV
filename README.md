function removeSpecificCharacters(str) {
    return str.replace(/[.*+?^${}]/g, ''); // Remove only these characters
}

console.log(removeSpecificCharacters("Hello.*+?^${}()|[]\\World")); 
// Output: "Hello()|[]\World"