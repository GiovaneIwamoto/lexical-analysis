# LEXICAL ANALYSIS

### **INTRO**

Implementation of the lexical analyzer for the MiniJava programming language with some extensions. MiniJava is a subset of Java, and its lexical analyzer should be able to recognize and return the tokens of the language specified in this document, which will later be terminal symbols of the grammar that specifies the language's accepted constructs.

### **TOKENS**

`1. IDENTIFIERS` A sequence of letters, digits, and underscores, always starting with a letter. The language distinguishes between uppercase and lowercase letters.

`2. INTEGER LITERALS` A sequence of decimal digits representing an integer number.

`3. OPERATORS`

`4. SEPARATORS`

`5. RESERVED WORDS` boolean, class, else, extends, false, if, int, length,
main, new, public, return, static, String, System.out.println, this, true, void, and while.

`6. COMMENTS` Comments should be ignored. There are two types: line comments and block comments.

`7. WHITESPACE` Whitespace should be ignored. It includes \n \t \r \f.

### **NOTE**

• "System.out.println" should be treated as a single reserved word and not as a method call.

• Reserved words are recognized as identifiers, except for "System.out.println" because it doesn't match the pattern of identifiers.

### **COMPILE AND EXECUTE**

`g++ -Wall \*.cpp -o mjc`
`./mjc program.mj`

### **AUTHOR**

-   Giovane Hashinokuti Iwamoto - Computer Science student at UFMS - Brazil - MS

I am always open to receiving constructive criticism and suggestions for improvement in my developed code. I believe that feedback is an essential part of the learning and growth process, and I am eager to learn from others and make my code the best it can be. Whether it's a minor tweak or a major overhaul, I am willing to consider all suggestions and implement the changes that will benefit my code and its users.
