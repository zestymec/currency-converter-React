# 💱 Currency Converter | React.js Project

Hi there! 👋 I'm a Junior Developer (about 4 months into my coding journey), and this is one of my most exciting projects yet. Building this Currency Converter helped me bridge the gap between "writing code" and "building a real-world product."

I built this specifically to master how **Data Flows** in React, especially when dealing with live APIs.

[**🌐 View Live Demo**](https://currency-converter-react-blond.vercel.app/)

---

## 🚀 Why I Built This (The Learning Curve)

Instead of just building a simple calculator, I wanted to tackle something that uses real data. This project was my "deep dive" into:

* **Custom Hooks:** I didn't want my `App.jsx` to be messy. So, I built `useCurrencyInfo`—a custom hook that acts as a dedicated "Data Fetcher."
* **Component Thinking:** I learned the **DRY (Don't Repeat Yourself)** principle by creating a reusable `InputBox`. I used it for both "From" and "To" sections, which made the code much cleaner.
* **State Management:** Managing four different states (`amount`, `from`, `to`, `convertedAmount`) and keeping them synced was a great challenge.
* **Handling APIs:** Learning how to fetch, parse JSON, and handle objects using `Object.keys()` to populate dropdowns.

## 🛠️ How It Works (Under the Hood)

### 1. The Logic Engine 🧠
The app uses a real-time API. Every time you change the "From" currency, my **Custom Hook** triggers a fresh fetch request. 

### 2. The Calculation 🔢
It’s not magic, it’s Math! The app takes your input and multiplies it by the specific rate fetched from the API:
`Converted Total = Amount * Rate[Target_Currency]`

### 3. The Swap Feature 🔄
One of my favorite features! It flips the currencies and the amounts instantly, so you don't have to re-type everything.

## 💻 Tech Stack Used

* **React.js** (Vite for a blazing fast setup)
* **Tailwind CSS** (For that smooth Glassmorphism UI)
* **JavaScript (ES6+)** (Map, Filters, and Async/Await concepts)
* **Vercel** (For Deployment)

## ⚙️ How to Run This Locally

If you want to play around with the code:

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/zestymec/currency-converter-React.git](https://github.com/zestymec/currency-converter-React.git)
    ```
2.  **Install the "Engine" (Packages):**
    ```bash
    npm install
    ```
3.  **Start the Project:**
    ```bash
    npm run dev
    ```

---

## 👨‍💻 Let's Connect!

I am constantly learning and growing. If you have any feedback or just want to talk about React, let's connect:

* **LinkedIn:** [Muhammad Umer Aziz](https://www.linkedin.com/in/zestymec/)
* **GitHub:** [@zestymec](https://github.com/zestymec)

---
*Inspired by the 'Chai aur Code' series. Built with ☕ and Logic.*