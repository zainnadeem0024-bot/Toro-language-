# 🐂 TORO Language  

TORO ek **custom programming language** hai jo Python ke upar bani hai.  
Iska goal hai programming ko **bhot easy aur mazaydaar** banana — simple keywords aur unique syntax ke sath.  

---

## ✨ Features  

- `show "text"` → Screen pe text print karega  
- `ask "question"` → User se input lega  
- `repeat N { ... }` → Loop chalane ke liye (N dafa repeat)  
- `if condition { ... } else { ... }` → Simple if-else statement  
- `make var = value` → Variable declare karne ke liye  
- `listy = [1, 2, 3]` → Special TORO list type  
- `. ye comments hain` (Python/Java jaisa `#` ya `//` nahi)  

---

## 🛠 Example Code (`main.toro`)  

```toro
. Ye ek simple program hai TORO language me

make name = ask "Tumhara naam kya hai?"
show "Hello " + name

repeat 3 {
    show "TORO language is awesome!"
}

make x = 5
if x > 3 {
    show "X bada hai 3 se"
} else {
    show "X chota ya barabar hai 3 ke"
}# Toro-language-
This is new toro language made by Syed Zain hussain 
