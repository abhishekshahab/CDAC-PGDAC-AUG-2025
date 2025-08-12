# 📚 Logic Building Session (Day 1)

## 📌 Topics Covered
- Introduction to Data Structures
- Introduction to Algorithms
- Basics of Java
- Exploring Java

---

## 1️⃣ Introduction to Data Structures
The name "Data Structure" is a combination of two words: "Data" and "Structure". Let's go over each word individually:

Data: Data is information that must be processed and stored in a computer. Data can be anything from numbers to characters to dates to photos to videos.

Structure: Structure refers to how data is structured. It specifies the relationship between various data elements and how they are kept in memory. The structure has an impact on the efficiency of data operations.
 | DATA       | STRUCTURE                          |
|------------|------------------------------------|
| Numbers    | Methods     of                     |
| Characters |       organising       and         |
| Dates      |      storing    the   data         |
| Photos     |                                    |
| Videos     |                                    |


Dekho baba ab simple language me :

Data Structure = Data ko store aur arrange karne ka tarika
Jisse hum us data ko fast aur easy way me access, update, ya delete kar sakein.
 💡Example: 
- Tumhare phone me contacts → alphabetically sorted list (Ye structure hai).
- Har contact ke andar naam, number, photo → Ye data hai.

Jaise almirah me kapde fold karke alag-alag shelf me rakhte ho, waise hi Data Structure me hum data ko arrange karte hain taaki zarurat padte hi turant mil jaye.

📌 Real-World Example of Data Structure
Example: 📱 Phone Contacts App

1. Data: Har contact ka naam, phone number, email, photo.

2. Data Structure:
     -Contacts alphabetically sorted list me store hote hain (Array/List).
     -Har contact ke details ek saath group me rakhe hote hain (Record / Object).

3. Kaam kaise hota hai:

    -Jab tum search bar me "Abhishek" likhte ho → App binary search jaisa fast algorithm use karke result dikhata hai.
    -Agar tum naya contact add karo → List me correct alphabetical position me insert ho jata hai.

💡 Why it’s efficient: 
Agar contacts randomly store hote, tumhe pura list scroll karni padti.
Sorted list + fast searching = Time bach gaya, kaam fast ho gaya.

---

## 2️⃣ Introduction to Algorithms
Algorithm – A set of clear, step-by-step instructions to solve a problem or perform a task.

💡 Like a recipe tells you how to cook a dish, an algorithm tells the computer how to do something, step by step.
Dekho baba ab simple language me : 
Algorithm = Kisi kaam ko step-by-step tarike se karne ka plan.
💡 Example :
   Chai banane ka recipe → Ye ek algorithm hai.
    1. Paani garam karo
    2. Chai patti daalo
    3. Doodh aur shakkar daalo
    4. Cup me daal ke serve karo
Computer programming me, algorithm hota hai ek clear steps ka set jisse computer samajh sake ki kaam kaise karna hai.

📌 Characteristics of a good algorithm:
Clear & Unambiguous – Steps ka matlab clear ho.
Well-defined Inputs & Outputs – Kya lena hai, kya dena hai clear ho.
Finite Steps – Kabhi na rukne wala loop nahi hona chahiye (jab tak intentionally infinite na ho).

📌 Ways to Write/Represent an Algorithm
| Method                  | Description                                                                      | Example                                                             |
| ----------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| **1. Natural Language** | Simple sentences in normal English (or any language) describing each step        | “Step 1: Take two numbers. Step 2: Add them. Step 3: Show the sum.” |
| **2. Pseudocode**       | Writing algorithm steps in a code-like but human-readable way (no strict syntax) | `sum ← a + b` <br> `print(sum)`                                     |
| **3. Flowchart**        | Visual diagram using shapes/arrows to show step-by-step flow                     | 
| **4. Actual Code**      | Writing in a real programming language (Java, Python, C, etc.)                   | `System.out.println(a + b);`                                  


Logic Building Phase (Days 1–6) → Mostly Natural Language + Flowchart + Pseudocode.

Baad me → Actual Code (Java) me implement karoge.


Flowchart – A diagram that shows the steps of a process or algorithm using shapes and arrows.
Shapes:
 – Oval → Start / End
 – Rectangle → Process / Action
 – Diamond → Decision (Yes/No)
 – Arrow → Flow direction

 ## 🖊 Creating Flowcharts

Flowcharts can be created in two ways:

1. **Manual Method (Pen & Paper)**  
   - Draw shapes (ovals, rectangles, diamonds) and connect them with arrows.  
   - Useful for quick logic sketches during brainstorming.

2. **Digital Method (Online / Software Tools)**  
   - Use flowchart-making tools for a clean and shareable diagram.  
   - Example: **RAPTOR** – A free flowchart-based programming environment.  
     - Website: [https://raptor.martincarlisle.com/](https://raptor.martincarlisle.com/)  
     - Just download and install. It allows you to create flowcharts and directly run them as programs.

---
## 3️⃣ Basics of Java
Java is a **high-level, object-oriented, platform-independent** programming language developed by **James Gosling** in 1995 at **Sun Microsystems**.


> 💡 **High-Level Language:**  
> A programming language that is close to human language and easy to read/write.  
> - Uses English-like words (e.g., `if`, `while`, `class`)  
> - Hides hardware details from the programmer  
> - Compiler/Interpreter converts it into machine code for execution  
> **Example:** Java, Python, C++ are high-level languages.

---

> 💡 **Object-Oriented Language:**
> this is the language which allows us to create the object of that class and use that object anywhere outside the class.
> Programming ka aisa style jisme hum apne code ko **objects** me organize karte hain.  
> - **Object** = Real-world cheez (e.g., Car, Student, Bank Account)  
> - Har object ke paas **properties** (data) aur **methods** (kaam) hote hain.  
> - Isse code easy to manage, reuse, aur samajhna simple ho jata hai.  
> **Example:** Java, C++, Python.

> 💡 **Platform Independent:**  
> Java me ek baar program banao, to wo Windows, Mac, Linux sab pe chal sakta hai.  
> Tumhe har OS ke liye alag se code likhne ki zarurat nahi hoti.  
> - Java code compile hoke **Bytecode** banta hai.  
> - Bytecode ko **JVM** har OS pe run kar deta hai.  


### 🔹 Key Facts
- **Original Name:** OAK (renamed to Java in 1995)
- **Platform Independent:** Write Once, Run Anywhere (WORA) 
- **Type:** Open-source & free
- **Execution:** Compiled into bytecode → runs on JVM
- **Multithreading:** multiProccesing at a same time is a multithreading .
- **just in time comPiler JIT:** JIT comPiler allows you to code run faster , jo repetitive code he usko kahi memory me save krke rakhta he jisse double code likhna na Pde
- **Garbage collection:** the objects which are no use to me iam going to delete them with the help of garbage collection. and java does this work for you freely, java me garbage collector ko bulana nahi pdta unlike other lanugages unlike c++ and c 
---

### 🔹 Java Components
1. **JDK (Java Development Kit):**  this is a huge package , this is a platform specific(jdk windows, mac, linux, ke liye alag hoga),  Contains tools to develop, compile programs , only write and comPile the code .
2. **JRE** | Run Java programs | JVM, Libraries |
3. **JVM** | jvm is platform independent(jvm sabhi me same hota he jo java ko platform independent banata he),  Execute bytecode on your OS | - |


1️⃣ JDK – Java Development Kit
Purpose: Java program banane aur run karne ka complete toolkit.
Contains:
  - Compiler (javac) → .java file ko .class (bytecode) me badalta hai.
  - Development Tools → Debugger, JavaDoc, jar creator, etc.
  -JRE → Program run karne ke liye environment.
Use: Agar tum Java code likh rahe ho ya compile kar rahe ho → tumhe JDK chahiye.
💡 Example:
Code likha → javac MyCode.java → bytecode bana → JVM pe run hua.

2️⃣ JRE – Java Runtime Environment
Purpose: Java program run karne ke liye environment provide karta hai.
Contains:
   -JVM (Java Virtual Machine) → bytecode ko execute karta hai.
   -Java Class Libraries (e.g., java.lang, java.io, java.util) → ready-made functions.
   -Java Standard Extensions (e.g., JavaFX, JCE) → extra features.

Use: Agar tum sirf Java program chalana chahte ho, coding nahi, to JRE enough hai.

3️⃣ JVM – Java Virtual Machine
Purpose: Java bytecode ko machine code me badal kar execute karta hai.
Platform-specific: Windows JVM, Mac JVM alag hote hain, lekin bytecode same hota hai.

Main parts:
 -Heap Memory → Objects & data store karne ke liye.
 -Stack Memory → Method calls & local variables ke liye.
- Non-Heap Memory → Class metadata, method area.
-PC Register → Current instruction ka address store karta hai.le
-JIT Compiler (Just-In-Time) → Bytecode ko jaldi se native machine code me convert karke performance badhata hai.

Diagram ka flow:
JDK (Development tools + Compiler + JRE)
     ↓
JRE (JVM + Libraries + Extensions)
     ↓
JVM (Executes Bytecode → Machine Code)


### 🔹 CLASSES AND OBJECTS
- a class is a template to create objects having similar properties and behavior, or in other words, we can say that a class is a blueprint for objects.
- an object is an instance of a class. for example, the animal type dog is class, while a particular dog named tommy is an object of the Dog class.

### 🔹 lets write our first java code Hello world!


class Car{
	public static void main (String [] args){
		System.out.println("Hello CDAC!!");
	}
}



jvm start karega main se run krna .
- car is class name
- public is a keyword (reserve word)
- static is also reserve word
- void means method ka return type , means method kuch nahi return karti he
- main is something jo ki java me pehle se hi uska record he
- string [] means array of string
- args means anything
- system.out.println is a method
