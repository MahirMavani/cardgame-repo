# 🃏 Java Card Deck & Dealer Simulator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Java](https://img.shields.io/badge/Java-17%2B-orange.svg)](https://www.oracle.com/java/)

> **An Object-Oriented Programming (OOP) standard card deck management and dealing engine in Java, demonstrating clean encapsulation, modular state management, and algorithmic shuffling.**

---

## 📌 Features

- **Standard 52-Card Representation**: Complete implementation of card ranks (Ace through King) and suits (Hearts, Diamonds, Clubs, Spades).
- **Algorithmic Deck Shuffling**: Cryptographically fair or pseudo-random in-place Fisher-Yates array shuffling.
- **Dealer Engine**: Modular hand distribution, card drawing, and state validation.
- **UML Architecture**: Complete class diagram specification documented in [`diagram java carddeck.jpg`](diagram%20java%20carddeck.jpg).

---

## 🏗️ Project Architecture

```text
cardgame-repo/
├── src/
│   ├── Card.java      # Card entity encapsulating Rank, Suit, and display methods
│   └── Dealer.java    # Dealer & Deck state controller (shuffle, deal, reset)
├── diagram java carddeck.jpg # Architectural UML diagram
├── LICENSE            # MIT License
└── README.md          # Project documentation
```

---

## 🚀 Compilation & Execution

Compile and run using the Java Development Kit (JDK):

```bash
# Compile source files
javac src/*.java -d out/

# Execute Dealer simulation
java -cp out Dealer
```

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
