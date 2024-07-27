# LEXICAL ANALYSIS

### **OVERVIEW**

Implementation of the lexical analyzer for the MiniJava programming language with some extensions.

> [!NOTE]
> MiniJava is a subset of Java, and its lexical analyzer should be able to recognize and return the tokens of the language specified in this document, which will later be terminal symbols of the grammar that specifies the language's accepted constructs.

[![Icons](https://skillicons.dev/icons?i=cpp,java,regex&theme=dark)](https://skillicons.dev)

---

### **TOKENS**

> [!IMPORTANT]
> System.out.println should be treated as a single reserved word and not as a method call.

```ruby
[IDENTIFIERS] A sequence of letters, digits, and underscores, always starting with a letter.

[INTEGER LITERALS] A sequence of decimal digits representing an integer number.

[RESERVED WORDS] boolean, class, else, extends, false, if, int, length, main, new, public, return, static, String, System.out.println, this, true, void, and while.

[COMMENTS] Comments should be ignored. There are two types: line comments and block comments.

[WHITESPACE] Whitespace should be ignored. It includes \n \t \r \f.

[OPERATORS] and [SEPARATORS]
```

> [!WARNING]
> Reserved words are recognized as identifiers, with the notable exception of System.out.println, because it doesn't match the typical pattern of identifiers.

---

### **COMPILE AND EXECUTE**

```java
$ g++ -Wall \*.cpp -o mjc
$ ./mjc program.mj
```

---

### **AUTHOR**

- Giovane Hashinokuti Iwamoto - Computer Science student at UFMS - Brazil - MS

I am always open to receiving constructive criticism and suggestions for improvement in my developed code. I believe that feedback is an essential part of the learning and growth process, and I am eager to learn from others and make my code the best it can be. Whether it's a minor tweak or a major overhaul, I am willing to consider all suggestions and implement the changes that will benefit my code and its users.
