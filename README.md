# Compiler For PsuedoCode Using Flex And Bison
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/4ad79223-4b75-4219-b41f-a5a73e0111b3)# Compiler_For_Psuedocode-Using-Flex-and-Bison-
Developed a compiler for pesudocode using FLEX and BISON. Was successful in illustrating various phases of compilation by giving the output in each phase like TOKENS, SYMTAB, AST, INTERMEDIATE CODE, FINAL OUTPUT
## **INTRODUCTION**
A compiler is a translator whose source language is a high-level language and whose object language is close to the machine language of an actual computer. Our aim is to design a compiler that compiles code that is written in pseudo code format. 
## **Phases of Compiler Design**
* Lexical Analysis
* Syntax Analysis
* Semantic Analysis
* Intermediate Code Generation
* Code Optimization
* Code Generation
## **Flex**
* Flex (Fast Lexical Analyzer Generator) is a powerful tool used for generating lexical analyzers or scanners for programming languages. It simplifies the process of implementing the lexical analysis phase in a compiler or interpreter.
* Regular Expression-Based Matching: Flex allows you to define token patterns using regular expressions. These patterns are matched against the input text to identify tokens.
* Token Actions: Flex allows you to associate actions with each token pattern. These actions can be customized code snippets that get executed whenever a token is matched. Actions are often used to perform tasks like updating counters, manipulating data structures, or calling specific functions.
* Automatic Code Generation: Flex takes the input file containing token specifications and generates efficient C/C++ code for the lexical analyzer. This generated code includes the scanner function that can be seamlessly integrated into the compiler or interpreter.
## **Operators and Keywords**
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/37e1ac9b-5ad9-4c6b-a00a-10021c883e55)
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/893a2669-8087-4a12-b18d-f5931f944aea)
## **Regular Expression**
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/eec95e1b-fa54-4d41-a6ad-9a514a7523f5)
## **LEXICAL ANALYSIS OUTPUT**
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/fd0100d4-44ff-4a13-a54c-8be33ee4ecd3)
## **OUTPUT SYMTAB**
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/33b27b6b-dba0-439e-9aad-d4215a1b12fa)
## **OUTPUT LEXTAB**
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/bdbfdb1b-8744-4c5e-ba51-025f3127fead)
## **SYNTAX ANALYSIS**
  A parser is a program which determines if its input is syntactically valid and determines its structure.
The compiler verifies that the arrangement of tokens follows the grammar rules of the programming language. It constructs a parse tree or an abstract syntax tree (AST) to represent the syntactic structure of the program.Each node has an operator, and the operator's operands are the node's children. This is primarily done to ensure that the syntax of the given statements is correct and adheres to the language's pre-defined rules. If the syntax is incorrect, it generates a syntax error.
Yacc and Bison are tools for generating parsers: programs which recognize the structure grammatical structure of programs. Bison is a faster version of Yacc


## **BISON**
  * Bison is a powerful tool used for generating parsers or syntax analyzers for programming languages. It works in conjunction with a lexical analyzer (often implemented using Flex) to process the input source code and identify the syntactic structure of the program.
* Grammar Specification: Bison uses a formal grammar specification to define the syntax rules of a programming language. This specification is typically written in a notation called BNF (Backus-Naur Form) or a variant of it.
* Context-Free Grammar: Bison supports context-free grammars, which describe the syntactic structure of a language without considering the context or meaning of the program.

## **BISON FILE**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/a18f49fa-563a-4efc-a2e3-5628b468051f)

## **GRAMMAR**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/2a5df477-1939-40f9-9d10-43706bb72d46)

## **INPUT**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/109de13e-f323-4ca8-a5e1-e19f41e4fea7)

## **AST SKELETON**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/1f91eee7-802d-473f-890a-3728c24895eb)

## **OUTPUT AST**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/43acd05b-4823-419a-8ff1-f85e7ffa85c1)
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/9d83d88a-4173-46c0-b1df-b4d83e2ee287)

## **SEMANTIC ANALYSIS**
  The compiler performs semantic analysis to check the correctness and meaning of the program. It ensures that variables are declared before use, enforces type compatibility rules, performs constant folding, and detects other semantic errors

## **INTERMEDIATE CODE GENERATION**
  The compiler may generate an intermediate representation of the program, which is a lower-level code that is closer to the target machine code but still independent of the specific hardware. 
The intermediate code is optimized for size or performance.

## **INTERMEDIATE CODE**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/3a29b036-d497-4cb9-9874-a1469838b207)
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/3e6f3b46-552a-464c-b36a-768ac59de42f)

## **OUTPUT INTERMEDIATE CODE**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/4d284cb6-4d11-46bf-92ba-5232cd142e0a)
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/b598de19-93ca-4190-9fe6-554d8eb70791)

## **CODE OPTIMIZATION**
  The compiler applies various optimization techniques to improve the efficiency of the generated code. It optimizes the intermediate code by eliminating redundant computations, reducing memory usage, and improving execution speed.

## **EVALUATION FUNCTION-CORE OF EVALUATION**
  ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/ce1b0783-dec3-427c-a784-ff43d9885b8f)

## **CODE GENERATION**
  The compiler generates the target code, which can be machine code, assembly language, or bytecode, depending on the target platform. This code is executable by the computer's hardware or a virtual machine.

## **OUTPUT**
 ![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/367a1f42-ddbd-4359-8ea3-26df9ecac4f4)
![image](https://github.com/AryanKulathinal/Compiler_For_Psuedocode-Using-Flex-and-Bison-/assets/116480303/dc2c1eec-c693-4bcd-a579-e0488c6dd210)

## **ERROR HANDLING**
  You can define how to recover from a syntax error by writing rules to recognize the special token error. This is a terminal symbol that is always defined and reserved for error handling.
The Yacc/Bison parser generates an error token whenever a syntax error happens.










