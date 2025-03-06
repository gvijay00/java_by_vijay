### **JDK Architecture in Java**  

The **Java Development Kit (JDK)** is a software development kit that provides the necessary tools to develop, compile, and run Java applications. It consists of various components, including the **JVM (Java Virtual Machine), JRE (Java Runtime Environment), and Development Tools**.

---

## **1. Components of JDK**
The JDK consists of the following main components:

1. **Java Compiler (`javac`)**  
   - Converts Java source code (`.java`) into bytecode (`.class`).
   - Example:  
     ```
     javac HelloWorld.java
     ```
  
2. **Java Virtual Machine (JVM)**  
   - Executes the compiled bytecode (`.class` file).
   - Converts bytecode into machine code using **JIT (Just-In-Time) Compiler**.
  
3. **Java Runtime Environment (JRE)**  
   - A part of the JDK that provides libraries and JVM to run Java programs.
   - Includes **Java libraries** (`rt.jar`) and runtime components.

4. **Java API (Application Programming Interface)**  
   - A collection of predefined classes and methods (like `java.lang`, `java.io`, `java.util`, etc.).
  
5. **Java Debugger (`jdb`)**  
   - A tool to debug Java programs and fix errors.

6. **Java Archive Tool (`jar`)**  
   - Used to package Java files into a `.jar` file.

7. **Other Development Tools**  
   - **`javap`** → Disassembler to view bytecode.  
   - **`javadoc`** → Generates documentation from comments.  
   - **`keytool`** → Manages security keys and certificates.

---

## **2. JDK Architecture Diagram**
```
c:\Users\gurug\Downloads\gfgjdk-660x423.jpg
```



## **3. Working of JDK**
1. **Write Java Code:**  
   - Create a `.java` file with Java code.

2. **Compile Code (`javac`)**  
   - Converts `.java` files into bytecode (`.class`).

3. **JVM Execution:**  
   - Class Loader loads `.class` files.
   - Execution Engine (JIT Compiler) translates bytecode into machine code.
   - The program runs on the operating system.

---

## **4. Difference Between JDK, JRE, and JVM**
| Feature  | JDK (Java Development Kit) | JRE (Java Runtime Environment) | JVM (Java Virtual Machine) |
|----------|-----------------|-----------------|-----------------|
| **Contains** | JRE + Development Tools | JVM + Libraries | Only JVM |
| **Used for** | Development + Execution | Only Execution | Running Java bytecode |
| **Includes** | Compiler, Debugger, JRE, JVM | JVM, Java Libraries | Just Execution Engine |

---
### **Conclusion**
- **JDK** is used for developing Java applications.
- **JRE** is needed to run Java programs.
- **JVM** executes Java bytecode.
- The **JIT Compiler** improves performance by converting bytecode to machine code at runtime.
