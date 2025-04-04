# 📱 Phone Number Identifier (Nepal)

A **Java Swing GUI application** that identifies the telecom service provider (NTC, Ncell, Smart Cell, Hello Mobile, UTL) of a given **10-digit Nepali phone number**.

---

## 🔍 Features

- Detects whether a number belongs to:
  - 📞 NTC
  - 📞 Ncell
  - 📞 Smart Cell
  - 📞 Hello Mobile
  - 📞 UTL
- Real-time identification as you press enter.
- Validates the number to ensure it follows the **Nepali mobile format** (starts with `9`, and is exactly 10 digits).
- Simple and clean user interface using **Java Swing**.
- Built using **NetBeans IDE**.

---

## 🧠 Logic Used

The app checks the prefix of the 10-digit number:
- `984`, `985`, `986` → NTC
- `980`, `981`, `982` → NCELL
- `988` → Smart Cell
- `972` → UTL
- `961`, `962` → Smart Cell
- `963` → Hello Mobile

Numbers not matching these rules or not 10 digits long are marked as **invalid**.

---

## 🛠️ How to Run

1. Clone or download the repository.
2. Open the project in **NetBeans IDE**.
3. Run the `Home.java` file.
4. Type a Nepali phone number and press **Enter**.
5. See the result below the input field.

OR.
Simply run the jar file.
---

## 📸 Screenshots:
![image](https://github.com/user-attachments/assets/ff6defbe-bed4-42a2-9ff8-f63572adb88c)

![image](https://github.com/user-attachments/assets/6258e919-b096-47e4-bd67-621c59b7ff02)
![image](https://github.com/user-attachments/assets/0959729f-8df1-4443-bc14-8fb875802823)

---

## 📂 Project Structure

```
Phone Number Identifier/
│
├── src/
│   └── number/identifier/
│       └── Home.java         # Main JFrame for UI and logic
│
└── README.md                 # This documentation
```

---
Please see master branch to view the source code or there is jar file in main branch
## 👨‍💻 Author

**Prajwol Chand**  
Made with ❤️ for Nepal.

---
