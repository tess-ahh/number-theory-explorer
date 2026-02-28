# 🔢 Number Theory Concepts Explorer

An interactive, browser-based tool for exploring core **Number Theory** algorithms with full step-by-step solutions. No installation required — just open the HTML file in any browser.

## 🚀 Live Demo

> **[▶ Open the App](https://YOUR-USERNAME.github.io/number-theory-explorer/)**  
> *(Replace with your actual GitHub Pages URL after publishing)*

---

## 📌 Features

The explorer covers **9 core Number Theory topics**, each with detailed intermediate steps:

| Module | Description |
|--------|-------------|
| **GCD / Extended GCD** | Euclidean & Extended Euclidean Algorithm with coefficient computation |
| **Primality & Factorization** | Trial division primality test and prime factorization |
| **Modular Exponentiation** | Fast binary (repeated squaring) exponentiation — O(log n) |
| **Linear Congruences** | Solve ax ≡ b (mod m) with all incongruent solutions |
| **Chinese Remainder Theorem** | Solve systems of simultaneous congruences |
| **Euler's Totient Function** | Compute φ(n) using prime factorization formula |
| **Fermat's Little & Wilson's Theorem** | Verify theorems step-by-step for any prime |
| **Legendre & Jacobi Symbols** | Quadratic residue checking with reciprocity |
| **Diophantine Equations** | Solve ax + by = c in integers with general parametric solution |

---

## 🖥️ How to Run Locally

### Option 1 — VS Code + Live Server (Recommended)
1. Install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension in VS Code
2. Open `index.html` in VS Code
3. Right-click → **"Open with Live Server"**

### Option 2 — Just double-click
- Double-click `index.html` — it opens directly in your browser. No setup needed.

---

## 📁 Project Structure

```
number-theory-explorer/
│
└── index.html       # Complete self-contained application (HTML + CSS + JS)
```

Everything is in a **single HTML file** — no frameworks, no dependencies, no build step.

---

## 🧮 Topics Covered

### GCD Algorithms
- **Euclidean Algorithm**: iterative division steps until remainder = 0
- **Extended Euclidean**: finds x, y such that `ax + by = gcd(a, b)`

### Primality & Factorization
- Trial division primality check up to √n
- Complete prime factorization with exponent notation (e.g. `360 = 2³ × 3² × 5`)

### Modular Exponentiation
- Binary (repeated squaring) method
- Handles very large exponents efficiently in O(log exp) steps

### Linear Congruences
- Solves `ax ≡ b (mod m)` using Extended GCD
- Returns all solutions modulo m/gcd(a,m)

### Chinese Remainder Theorem (CRT)
- Add/remove any number of congruences dynamically
- Computes unique solution mod N = product of all moduli

### Euler's Totient
- Uses the formula: `φ(n) = n · ∏(1 − 1/p)` over distinct prime divisors
- Shows how each prime factor reduces the count

### Fermat's Little Theorem & Wilson's Theorem
- Verifies `a^(p−1) ≡ 1 (mod p)` with full exponentiation trace
- Wilson: checks `(p−1)! ≡ −1 (mod p)` as a primality criterion

### Legendre & Jacobi Symbols
- Legendre `(a/p)`: determines quadratic residuosity mod prime p
- Jacobi `(a/n)`: generalization to odd composite n using quadratic reciprocity

### Linear Diophantine Equations
- Solves `ax + by = c` over integers
- Outputs particular solution and general parametric family

---

## 🛠️ Built With

- Pure **HTML5 + CSS3 + Vanilla JavaScript**
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) & [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) via Google Fonts
- Zero dependencies, zero build tools

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋 Author

Made with ❤️ for students and enthusiasts of Number Theory.  
Feel free to open issues or pull requests for improvements!