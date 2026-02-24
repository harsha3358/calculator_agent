#  GenAlpha CLI Calculator  
### Advanced Stack-Based Expression Evaluator

A command-line calculator built using core Data Structures (Arrays & Stacks) that supports:

- Infix to Postfix conversion
- Operator precedence handling
- Parentheses
- Decimal numbers
- Power operator (^)
- Undo functionality
- History tracking
- Clean OOP architecture

---

## 🧠 Concepts Implemented

| Concept | Implementation |
|----------|---------------|
| Stack | Expression evaluation & Undo feature |
| Array (Dynamic List) | History storage |
| Infix → Postfix | Stack-based parsing |
| Operator Precedence | Custom precedence logic |
| Time Complexity | O(n) per expression |

---

## ⚙️ Features

- ✅ Addition, Subtraction, Multiplication, Division
- ✅ Power operator (^)
- ✅ Decimal number support
- ✅ Parentheses support
- ✅ Undo last calculation
- ✅ Calculation history
- ✅ CLI interactive menu
- ✅ Error handling

---

## 🖥️ Example Inputs

```
2.5 + 3.5
5 ^ 2
2 + 3 * 4
( 2 + 3 ) ^ 2
```

---

## ▶️ How to Run

```bash
python genalpha_cli_calculator.py
```

---

## 🧪 Sample Output

```
Result: 6.0
Result: 25.0
Result: 14.0
Result: 25.0
```

---

## 📊 Time Complexity

| Operation | Complexity |
|------------|------------|
| Infix to Postfix | O(n) |
| Postfix Evaluation | O(n) |
| Undo | O(1) |
| History Append | O(1) |

---

## 📌 Project Architecture

```
CalculatorCLI
 ├── precedence()
 ├── infix_to_postfix()
 ├── evaluate_postfix()
 ├── calculate()
 ├── undo()
 └── show_history()
```

---



## 👨‍💻 Built With

- Python 3
- Core Data Structures
- Object-Oriented Programming

---

## 📜 License

MIT License
