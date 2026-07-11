# Bank-Management-System

# 🏦 Console Banking System

A lightweight, object-oriented console application written in C++ that simulates standard automated teller and banking systems. The application manages real-time ledger records, dynamic balance modifications, and operational transaction history via a secure terminal user interface.

---

## 🚀 Features

* **Dynamic Account Modeling:** Encapsulates distinct account states including client identity, validated account generation metrics, and active balancing algorithms.
* **Transactional Bookkeeping:** Tracks transaction history via a signed integer vector framework (deposits tracked positively, withdrawals tracked negatively).
* **Contextual Log Parsing:** Implements an automated lookup system to immediately parse and output the last 5 transactions or dynamically determine the peak absolute transaction volume.
* **Input Validation Architecture:** Enforces explicit state loops to handle runtime execution edge cases, mitigating system anomalies from invalid user commands.

---

## 🛠️ Tech Stack & Concepts

* **Language:** C++11 (or higher)
* **Paradigm:** Object-Oriented Programming (OOP)
* **Core Concepts:** Data encapsulation, constructor instantiation, function overloading, dynamic array parsing (`std::vector`).

---

## 📂 Project Structure & Architecture

The architecture relies entirely on the `BankAccount` class paradigm, split across logical layers:

* **State Management:** Holds primitive member variables ensuring clean data scoping per operational profile instance.
* **Transaction Controls:** Governs underlying mathematical operations (`deposit` / `withdraw`) modifying the main state block.
* **UI Menu Controller:** Houses the continuous menu evaluation loops controlling operational flow states down to explicit system exits (`exit(1)`).

---

## 💻 Getting Started

### Prerequisites
Ensure you have an updated `g++` compiler installed on your native development environment toolset.

### Compilation
Compile the source file using standard terminal flags:
```bash
g++ -O3 main.cpp -o BankingSystem
