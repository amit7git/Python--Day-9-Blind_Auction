# Day 9 – Blind Auction 🏷️

Part of my **100 Days of Python Projects** challenge.  
This project simulates a blind auction system where multiple users can place bids anonymously, and the program determines the highest bidder.

---

## 🚀 Project Overview
The Blind Auction Project is a console-based Python application that collects bids from multiple participants without revealing other bids. After all entries are submitted, the program evaluates and announces the highest bidder.

---

## 📚 What I Learned
- Using **dictionaries** to store key-value pairs (bidder name → bid amount)
- Implementing **loops** to handle multiple user inputs
- Applying **conditional logic** to compare values
- Writing reusable **functions** to determine the winner
- Managing program flow in an interactive console application

---

## 🛠 How It Works
1. The program displays an ASCII logo from the `art` module  
2. A user enters their name  
3. The user enters their bid amount  
4. The program asks if there are more bidders  
5. If yes → the screen clears and the next bidder enters  
6. If no → the program compares all bids  
7. The highest bidder is announced as the winner  

---

## 💡 Code Highlights
- Stored bidder information using a **dictionary**
- Used a **for loop** to find the highest bid
- Created a function to calculate and display the winner
- Controlled user interaction with conditional statements

---

## 🧪 Example
    Welcome to the Secret Auction Program.
    What is your name?: Amit
    What is your bid?: 250
    Are there any other bidders? Type 'yes' or 'no': yes
    
    What is your name?: Rahul
    What is your bid?: 300
    Are there any other bidders? Type 'yes' or 'no': no
    
    The winner is Rahul with a bid of $300
    
---

## ▶️ How to Run
1. Clone the repository  
2. Open the project folder  
3. Run the file using:


4. Follow the on-screen prompts  

---

## 🌐 Live Demo
https://amit7git.github.io/Python--Day-9-Blind_Auction
