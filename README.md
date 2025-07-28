# 🛒 MakolaStore – Multi-Country E-Commerce App

**MakolaStore** is a modular and scalable **React Native mobile app** designed to deliver a seamless shopping experience across countries. It allows users to browse and shop in **localized storefronts** such as Ghana and the USA, each powered by their own **WooCommerce stores**.

> Think Jumia meets Amazon — but country-smart and mobile-first.

---

## 🌍 Key Features

- 🌐 **Multi-Country Store Selection**  
  Choose between Ghana and US stores via welcome screen with flag icons

- 🔐 **Authentication**  
  JWT-based login/signup with token stored in AsyncStorage  
  ✅ Already working for the Ghana store (makolastore.com)

- 🏠 **Home Screen**  
  Displays product recommendations, flash sales, banners, and category icons

- 📁 **Categories & Products**  
  Browse products by categories with dynamic tabs and subcategories

- 🛍️ **Product Detail Screen**  
  View image gallery, variants, pricing, and "Add to Cart" button

- 🛒 **Cart & Checkout**  
  Manage cart items locally; place orders via WebView or API-based checkout

- 📦 **Order Tracking**  
  Track shipping status and delivery info using WooCommerce orders API

- 👤 **Profile Screen**  
  View account info, order history, and log out

- 🔔 **Push Notifications**  
  Notify users of new products (already implemented on Ghana store)

---

## ⚙️ Tech Stack

| Layer         | Stack/Tools                                 |
|---------------|----------------------------------------------|
| **Frontend**  | React Native, React Navigation, AsyncStorage |
| **Backend**   | WooCommerce REST API, JWT Auth               |
| **Notifications** | Custom PHP API in WooCommerce (Ghana)    |

---

## 🗂️ File Structure

```
/src
├── /components
│   ├── HeaderBar.js, SearchBar.js, CategoryIcons.js, ...
├── /constants
│   └── countries.js
├── /screens
│   ├── WelcomeScreen.js, CountrySelection.js, ...
├── /services
│   └── WooAPI.js
├── /context
│   └── CountryContext.js
├── App.js
```

---

## 🛠 Setup & Installation

```bash
# Clone the repo
git clone https://github.com/Blunttree-Gh/makolastore.git
cd makolastore

# Install dependencies
npm install

# Start the development server
npx expo start
```

---

## 🧭 Roadmap

- ✅ Ghana store authentication + push notifications complete
- 🚧 US store authentication and product sync in progress
- 📱 Complete category screen, order tracking, and full checkout flow
- 🔔 Replicate push notification logic for US store
- 📸 Add screenshots and app store preview
- 🌍 Deploy mobile app via Expo and Play Store

---

## 🙋🏽‍♂️ Author

**Jonathan Haile-Selassie Azembah**  
💼 Full-Stack Developer | Mobile Dev | Cybersecurity Enthusiast  
📧 blunttree8819@gmail.com  
🔗 [GitHub](https://github.com/Blunttree-Gh) | [LinkedIn](https://linkedin.com/in/agambah)

---

## 📄 License

MIT License — free to use with credit.

---

**Let’s power cross-border shopping with secure, scalable mobile commerce.**
