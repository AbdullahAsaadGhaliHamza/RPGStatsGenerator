# Stats Tool

Simple browser tool for managing and testing game stats.

You can tweak values, add custom stats, and export everything as JSON or CSV. Useful for balancing, prototyping, or just organizing numbers without opening Excel every time.

No setup needed. Just open the HTML file.

---

## What it does

- Lets you edit a bunch of common game stats  
- Supports different categories like base stats, damage types, proc chances, and more  
- Add your own custom stats anytime  
- Increase or decrease values quickly with buttons  
- Search through stats instantly  
- Export your data to JSON or CSV  
- Save and load projects  

---

## How to use

1. Open the HTML file in your browser  
2. Change any stat value directly or use the buttons  
3. Use the search bar if the list gets too long  
4. Add custom stats at the bottom or from the menu  
5. Export when you are done  

That is it

---

## Features

### Stat editing
Every stat has:
- Input field  
- Increment button  
- Decrement button  

Custom stats also have a remove button

---

### Categories

- Base Stats  
- Damage Types  
- Proc Chances  
- Tactical Stats  
- Custom Stats  

You can extend this however you want in the code

---

### Search

Type anything in the search bar and it filters the list instantly

---

### Export

You can export in two formats:

JSON
- Structured data  
- Good for saving projects or using in code  

CSV
- Easy to open in Excel or Google Sheets  

---

### Save and Load

- Save creates a JSON snapshot of your current setup  
- Load lets you restore it later  

---

### Import CSV

You can import stats from a CSV file using this format:

```
Category,Stat,Value
baseStats,Health,100
damageTypes,Fire,25
```

---

## Project structure

Just one file:

```
index.html
```

Everything is inside it. No dependencies, no build step.

---

## Why I made this

Mostly to avoid using spreadsheets for simple stat tweaking. It is faster to just open a page and start adjusting values.

---

## Notes

- Data is stored in memory only unless you export it  
- No backend  
- No validation for weird inputs so keep values reasonable  

---

## License

Do whatever you want with it
