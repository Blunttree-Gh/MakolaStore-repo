# 🛒 MakolaStore

**MakolaStore** is a multi-country e-commerce mobile app built with React Native and WooCommerce REST APIs. It allows users in Ghana, the US, and beyond to shop locally from their country-specific storefronts, all within one seamless app.

> Think of it as Jumia meets Amazon — built mobile-first for Africa and beyond.

---

## 🌍 Features

- 🗺️ Country-based store selection (Ghana, US, more)
- 🔐 Secure login/signup (JWT Auth – Ghana Store live)
- 🏠 Product browsing with flash sales, banners, categories
- 🛒 Cart & checkout flow
- 🚚 Order tracking
- 📱 Push notifications for new products (Ghana Store live)
- 👤 Profile screen with logout and order history
- 📦 Future US store support in progress

---

## 🧰 Tech Stack

| Layer        | Tools & Frameworks                          |
|--------------|----------------------------------------------|
| **Frontend** | React Native, TailwindCSS, Expo, Axios       |
| **Backend**  | WooCommerce REST API (JWT + Products + Orders) |
| **Auth**     | JWT via WP plugin                            |
| **Push**     | Custom WooCommerce functions + Expo Push API |
| **State**    | Context API, AsyncStorage                    |
| **Navigation** | React Navigation                          |

---

## 📦 Setup & Installation

```bash
# Clone the repo
git clone https://github.com/Blunttree-Gh/MakolaStore-repo.git
cd MakolaStore-repo

# Install dependencies
npm install

# Run development server
npx expo start
```

---

## 💻 Screenshots

### 🌍 Country Selector  
![Country](./makola-country.jpg)

### 🏠 Home Screen  
![Home](./makola-home.jpg)

### 🔐 Login Screen  
![Login](./makola-login.jpg)

### 🛒 Cart Screen  
![Cart](./makola-cart.jpg)

### 📦 Orders (Optional)  
![Orders](./makola-orders.jpg)

---

## 🗂 Project Structure

```
/src
├── /components       # Reusable UI components
├── /screens          # Screens: Home, Cart, Login, etc.
├── /services         # WooCommerce API logic
├── /context          # Country/store context
├── App.js            # Main entry
```

---

## 🚧 Status & Roadmap

- ✅ Ghana Store Auth, Notifications → DONE
- 🧪 US Store Integration → In progress
- 📱 Mobile demo (Expo Go) → Ready
- 🌐 Hosting WooCommerce API → Active (makolastore.com)

---

## 🙋🏽‍♂️ Author

**Jonathan Haile-Selassie Azembah**  
💼 Full-Stack Developer | Mobile Dev | Cybersecurity Enthusiast  
📧 blunttree8819@gmail.com  
🔗 [GitHub](https://github.com/Blunttree-Gh) • [LinkedIn](https://linkedin.com/in/agambah)

---

## 📄 License

MIT License — free to use with credit.

> Let’s build mobile-first African e-commerce experiences together.
