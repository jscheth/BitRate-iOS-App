# 💸 BitRate – iOS Bitcoin Exchange Rate App

**BitRate** is a beginner-friendly iOS app that fetches and displays real-time Bitcoin exchange rates in various world currencies. Built as a **learning project**, it’s designed to help you practice key iOS development skills like working with APIs, decoding JSON, and using Swift delegation patterns.

> ⚠️ Note: This app only shows BTC exchange rates and is built for educational purposes.

---

## 🔍 What You'll Learn

This project is ideal for practicing the following iOS development concepts:

- 🔗 **Networking with URLSession**: Learn how to make HTTP requests to a public API.
- 🧩 **JSON Parsing**: Use `JSONDecoder` to convert API responses into usable Swift data models.
- 🎯 **Protocols & Delegation**: Understand the flow of data using custom delegate methods.
- 💱 **UIPickerView**: Implement a currency picker and trigger updates based on user selection.
- 🎨 **UIKit Basics**: Create a clean, responsive UI using `UILabels`, `UIPickerView`, and Auto Layout.
- 🧠 **Error Handling**: Handle API errors gracefully and debug decoding issues.

---

## ⚙️ Features

- 📡 Fetches **live Bitcoin exchange rates**
- 💱 Supports over 20 fiat currencies
- 🔄 Updates the UI in real-time using delegation
- 🧪 Great for practicing **Model-View-Controller (MVC)** structure
- 🚫 No user input required — just select a currency from the picker

---

## 🌍 Supported Currencies

AUD, BRL, CAD, CNY, EUR, GBP, HKD, IDR, ILS, INR, JPY, MXN, NOK, NZD, PLN, RON, RUB, SEK, SGD, USD, ZAR

---

## 🧪 Technologies Used

- Swift 5
- UIKit
- URLSession
- JSONDecoder
- [CoinAPI](https://www.coinapi.io/) (REST API)
- Xcode Asset Catalog

---

## 📸 Screen Shots
![Simulator Screenshot - iPhone 16 Pro Max - 2025-04-15 at 15 30 38](https://github.com/user-attachments/assets/dc314571-fd29-4e18-baeb-16064e98baa2)
![Simulator Screenshot - iPhone 16 Pro Max - 2025-04-15 at 15 30 20](https://github.com/user-attachments/assets/0868a1cd-ea45-4c10-be6b-b70e377c421c)


---

## 🔑 API Integration

BitRate uses the [CoinAPI](https://www.coinapi.io/) for retrieving Bitcoin exchange rates.

