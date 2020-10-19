# Week One
* JDK, JRE, JVM
* Java Bytecode
* JVM
  * Class Loader
  * JVM Architecture
  * JVM Options

## 1. Compare JDK, JRE, JVM
![Compare JDK, JRE, JVM](https://cdn.techbeamers.com/wp-content/uploads/2019/03/JVM-vs-JRE-vs-JDK.png)

## 2. Java Bytecode
> Java bytecode is the instruction set for the Java Virtual Machine. It acts similar to an assembler which is an alias representation of a C++ code. As soon as a java program is compiled, java bytecode is generated. In more apt terms, java bytecode is the machine code in the form of a .class file. With the help of java bytecode we achieve platform independence in java.

### How does it works?
![How does it works](https://static.javatpoint.com/blog/images/java-bytecode.png)

## 3. JVM
### 3.1 Class Loader 
> Class loaders are responsible for loading Java classes during runtime dynamically to the JVM (Java Virtual Machine). Also, they are part of the JRE (Java Runtime Environment). Hence, the JVM doesn't need to know about the underlying files or file systems in order to run Java programs thanks to class loaders

### 3.2 JVM Architecture 
![JVM](https://www.javainterviewpoint.com/wp-content/uploads/2016/01/JVM-Architecture.png)

[Useful Resource](https://dzone.com/articles/jvm-architecture-explained)

### 3.3 JVM Options
* Heap
  * Xms: Specifying the initial lower bound of Java heap size.
  * Xmx: Specifying the initial upper bound of Java heap size.
  * Xmn: Specifying the initial Java heap size for the Eden generation.
  * Xss: Specifying the Java thread stack size.
* Non-Heap
  * MaxDirectMemorySize : specifies the maximum total size of java.nio (New I/O package) direct buffer allocations.
  * MaxMetaSpaceSize, MaxPermSize - Specifying the MetaSpace (the memory the VM uses to store class MetaData (the data that describes other data)) size.

#### Todo:
- [ ] Learn more about Direct Buffer VS Byte Buffer
