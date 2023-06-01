# LEXICAL ANALYSIS

### INTRO

Implementation of the lexical analyzer for the MiniJava programming language with some extensions. MiniJava is a subset of Java, and its lexical analyzer should be able to recognize and return the tokens of the language specified in this document, which will later be terminal symbols of the grammar that specifies the language's accepted constructs.

### TOKENS

IDENTIFIERS: A sequence of letters, digits, and underscores, always starting with a letter. The language distinguishes between uppercase and lowercase letters.

INTEGER LITERALS: A sequence of decimal digits representing an integer number.

OPERATORS: && < > + - \* / = == != !

SEPARATORS: ( ) [ ] { } ; . ,

RESERVED WORDS: boolean, class, else, extends, false, if, int, length,
main, new, public, return, static, String, System.out.println, this, true, void, and while.

COMMENTS: Comments should be ignored. There are two types: line comments (starting with // and extending to the end of the line) and block comments (starting with /_ and ending with _/ without nesting).

WHITESPACE: Whitespace should be ignored. It includes \n, \t, \r, and \f.

### COMPILE / EXECUTE

`g++ -Wall \*.cpp -o mjc`
`./mjc program.mj`

### AUTHOR

Giovane Hashinokuti Iwamoto - Computer Science student at UFMS - Brazil - MS
I am always open to receiving constructive criticism and suggestions for improvement in our developed code. I believe that feedback is an essential part of the learning and growth process, and I am eager to learn from others and make my code the best it can be. Whether it's a minor tweak or a major overhaul, I am willing to consider all suggestions and implement the changes that will benefit my code and its users.
