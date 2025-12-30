# 💰 Loan Calculator

A responsive web-based financial tool designed to calculate monthly loan payments based on user inputs. This project demonstrates core competencies in DOM manipulation, JavaScript logic, and responsive UI design.

## 🚀 Features
* **Real-time Calculation:** Instantly computes monthly payments.
* **User Input Validation:** Handles loan amount, interest rate, and repayment period.
* **Clean UI:** Modern, dark-themed interface using CSS Flexbox.
* **Responsive Design:** Works seamlessly on desktop and mobile devices.

## 🛠️ Technologies Used
* **Frontend:** HTML5, CSS3
* **Scripting:** JavaScript (ES6+)
* **Tools:** VS Code, Git/GitHub

## 📸 Screenshots
*(Add a screenshot of your project here. Example: `![Screenshot](./screenshot.png)`)*

## ⚙️ How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/rashmiwijemanna/loan-calculator.git](https://github.com/rashmiwijemanna/loan-calculator.git)
    ```
2.  Navigate to the project folder.
3.  Open `index.html` in your web browser.

## 🧮 How It Works (The Logic)
The application takes three inputs:
1.  **Loan Amount:** The principal amount borrowed.
2.  **Interest Rate:** The annual interest rate (%).
3.  **Months to Pay:** The duration of the loan.

The JavaScript logic calculates the monthly interest and adds it to the principal repayment portion to determine the total monthly installment.

```javascript
// Core Logic Snippet
interest = (loanAmount * (interestRate * 0.01)) / monthsToPay;
monthlyPayment = (loanAmount / monthsToPay + interest).toFixed(2);
