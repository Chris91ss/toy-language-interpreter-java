# Toy Language Interpreter (Java)

![Java](https://img.shields.io/badge/Java-11%2B-orange) ![License](https://img.shields.io/badge/License-MIT-purple) ![Status](https://img.shields.io/badge/Status-Active-brightgreen)

🚀 **Welcome to the Toy Language Interpreter!** This project is a feature-rich Java-based interpreter for a toy programming language, designed to provide a strong foundation in language interpretation. It supports core programming constructs such as expressions, conditionals, loops, multithreading, and a GUI debugger for real-time execution insights.

---

## 🛠️ Features

✅ **GUI Debugger** – Step through code execution and inspect variables using a user-friendly interface.

✅ **Comprehensive Data Types** – Supports integers, floats, booleans, strings, and references.

✅ **Powerful Expressions** – Evaluate arithmetic, logical, and relational expressions with precision.

✅ **Print Statements** – Output values and messages directly within the interpreter.

✅ **Conditional Logic** – Implement robust decision-making with if-else constructs.

✅ **Looping Constructs** – Utilize while and for loops to enable iterative operations.

✅ **Dynamic Memory Management** – Efficiently allocate and manage memory for variables at runtime.

✅ **Automatic Garbage Collection** – Reclaim memory for unused variables seamlessly.

✅ **Multithreading Support** – Execute multiple threads concurrently for parallel processing.

✅ **Synchronization Mechanism** – Ensure thread safety using synchronized operations.

✅ **Type Checking System** – Prevent type errors before execution for a robust development experience.


---

## 🚀 Future Enhancements

🔹 **Advanced Parsing Engine** – Implement a structured parser to improve code organization and execution.
🔹 **Expanded Language Features** – Extend support for functions, arrays, and object-oriented constructs.
🔹 **Optimized Performance** – Enhance execution speed and memory efficiency.
🔹 **Enhanced Debugging Tools** – Provide deeper insights into program execution and variable tracking.

---

## 📦 Getting Started

To set up and run the interpreter in **IntelliJ IDEA**:

### 1️⃣ Clone the Repository  
Open a terminal and run:  
```bash
 git clone https://github.com/Chris91ss/toy-lang-interpreter-java.git
```
Or, in **IntelliJ IDEA**:  
- Open IntelliJ IDEA → **Get from VCS** → Paste the repository URL → Clone.

### 2️⃣ Open the Project in IntelliJ IDEA  
- Open IntelliJ and select **Open**.  
- Navigate to the cloned repository folder and open it.  
- IntelliJ should automatically detect it as a **Java project**.

### 3️⃣ Set Up the Project  
- Ensure **Java SDK 11+** is installed and configured in **Project Structure** (Ctrl + Alt + Shift + S).  
- If using Gradle or Maven, import dependencies when prompted.  

### 4️⃣ Run the CLI or GUI Interpreter  
#### **Command-Line Interface (CLI)**  
To run the CLI version, execute:  
```bash
javac src/main/java/view/cli/CliInterpreter.java && java src/main/java/view/cli/CliInterpreter
```
Or, in IntelliJ:
- Navigate to `src/main/java/view/cli/CliInterpreter.java`.
- Right-click and select **Run 'CliInterpreter'**.

#### **Graphical User Interface (GUI)**  
To run the GUI version, execute:  
```bash
javac src/main/java/view/gui/toylanguageinterpreter/GuiInterpreter.java && java src/main/java/view/gui/toylanguageinterpreter/GuiInterpreter
```
Or, in IntelliJ:
- Navigate to `src/main/java/view/gui/toylanguageinterpreter/GuiInterpreter.java`.
- Right-click and select **Run 'GuiInterpreter'**.

### 5️⃣ Experiment with the Interpreter  
- Write test programs inside `.toy` files and execute them.  
- Use the **GUI Debugger** to step through execution.

---

## 📜 License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute the code under the terms specified in the [LICENSE](LICENSE) file.

🚀 **Stay tuned for further updates as we continue evolving this interpreter!** Happy coding! 🎯

