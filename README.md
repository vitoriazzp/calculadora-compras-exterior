🧮 Purchase Calculator
=====================================

Tool that automates the calculation of taxes on international purchases, converts amounts between Brazilian reais and US dollars, and verifies whether the store entered is on the Brazilian Federal Government's list of **partner stores**.

✨ Technologies
-------------
- ```HTML```, ```CSS``` and ```JavaScript vanilla```
- Static deployment  ```Vercel```
- ```Font Awesome Icons```

🚀 Features
------------------

- Automatic calculation of import taxes based on the value entered by the user.
- Conversion of values between Brazilian real and US dollar using the exchange rate displayed on the interface.
- Verification that the store entered is on the list of partner stores (with tax discounts).
- Interface focused on clearly displaying the final purchase price, reducing the cognitive load for the user.

📍 The Problem
-------------

On the official gov.br calculator, users must:  
- Manually check whether the store is on the list of partner stores.  
- Understand the tax difference themselves when the store is not a partner.  
- Convert amounts between Brazilian reais and US dollars on their own, even when viewing the exchange rate.

This makes the process more bureaucratic than it should be, especially for those who just want clarity on the final cost of their international purchase.

💡 The Solution
------------

Este projeto automatiza:  
- Calculation of import taxes based on the rules applied by the Federal Government.
- Conversion between Brazilian real and US dollar.
- Checking whether the store is on the list of partner stores.

This way, the person only needs to enter the basic purchase details and can immediately see the final price with the applicable taxes, without having to do separate calculations or consult separate lists.


🎨 Design Updates
----------------------

- Use of the **ShadCN** component library for more consistent visual structuring.
- Use of the **Font Awesome** icon library to reinforce the hierarchy and meaning of interface elements.


🚦 How to run the project
-----------------------

1. Clone the repository  
   ```bash
   git clone https://github.com/vitoriazzp/calculadora-compras-exterior.git
   cd calculadora-compras-exterior

2. Open the ```index.html``` file directly in your browser

- Double-click the file, or
- Use a Live Server extension in VS Code, if you prefer.

🌐 Deploy
----------------------
You can access the production version here:
https://calculadora-compras-exterior.vercel.app/

📅 Em breve
- Versão com layout otimizado para dispositivos móveis.
- Disponível também em inglês.
- Aperfeiçoamento visual com componentes reutilizáveis.
