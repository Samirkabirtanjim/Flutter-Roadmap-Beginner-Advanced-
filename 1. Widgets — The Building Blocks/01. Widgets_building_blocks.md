# Flutter: Widgets — The Building Blocks

In Flutter, **everything you see on the screen is a widget** — text, buttons, images, layouts, etc.  

There are **two main types of widgets**:

---

## 1️⃣ StatelessWidget
- A **StatelessWidget** does **NOT change** once it is built.  
- **Analogy:** Like a printed photo — it always looks the same.  
- **When to use:** Showing fixed text, icons, labels, pages where data does not change, and simple UI components.

---

## 2️⃣ StatefulWidget
- A **StatefulWidget** is a widget that **can change over time** — for example, when the user taps a button, scrolls, or types.  
- **Analogy:** Like a mobile phone screen — it changes when interacted with.  
- **When to use:** Buttons, counters, forms, when UI updates on user actions, data loading, animations, and anything that changes dynamically.

---

## 3️⃣ Quick Comparison

| Feature         | StatelessWidget | StatefulWidget |
|-----------------|----------------|----------------|
| Can change?     | ❌ No          | ✅ Yes         |
| Uses setState()?| ❌ No          | ✅ Yes         |
| Good for?       | Static UI      | Interactive / dynamic UI |
| Stores Data?    | ❌ No          | ✅ Yes         |

---
