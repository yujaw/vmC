# 🖥️ LC3 Virtual Machine

Welcome to the **LC3 Virtual Machine** project!  
A simple, educational VM written in C for learning, experimentation, and fun.

---

## ✨ Features

- 🧮 **Implements the full LC3 instruction set**
- 🗃️ **Memory-mapped I/O and registers**
- 🛠️ **Easy to extend and modify**
- 📝 **Well-commented, readable code**

---

## 📦 Getting Started

1. **Clone the repo:**
    ```bash
    git clone https://github.com/yourusername/vm.git
    cd vm
    ```

2. **Compile the VM:**
    ```bash
    gcc -o lc3vm vm.c
    ```

3. **Run the VM with an LC3 image:**
    ```bash
    ./lc3vm [image-file1.obj] ...
    ```

---

## 🧑‍💻 Usage

- Add new instructions or modify behavior in `vm.c`
- Try out sample LC3 programs in the `examples/` folder
- Read more about the architecture in the `docs/` folder

---

## 🗂️ Code Overview

- **Registers:** General purpose (R0–R7), PC, and condition flags
- **Memory:** 65536 16-bit locations, including memory-mapped I/O
- **Instruction Cycle:** Fetch, decode, execute loop
- **Trap Routines:** Keyboard input, output, halt, etc.

---

> 🚀 Dive into the code to learn how a real virtual machine works!

---

## 🤝 Contributing

Contributions are welcome!  
Open an issue or submit a pull request to get involved.

---

## 📄 License

Licensed under the MIT License.

---

> Made with ❤️ for learning and exploration!
