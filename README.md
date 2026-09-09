# Croma Mart – React E-Commerce Application

Croma Mart is a **modern React-based e-commerce web application** that demonstrates real-world shopping cart functionality, global state management, product filtering, authentication flow, and a polished user interface.

The project is built with a focus on **clean architecture, reusable components, and practical business logic**, making it suitable for learning, portfolio showcase, and real-world frontend practice.

---
## Live Demo



## Screenshots

### Home Page
<img width="1917" height="922" alt="Home page" src="https://github.com/user-attachments/assets/13f63f58-1597-4030-8b45-64461aff7492" />

### Sign In Page

<img width="955" height="410" alt="Sign_In_Page" src="https://github.com/user-attachments/assets/2741a943-acad-40d4-9946-0c2303c05670" />


### Explore Product Section

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d524bace-5f5e-46ce-a805-b30775640497" />


### Filtering Product Based on Category or Price

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/0722f39b-03e8-41bf-afbf-fc91fdedd0cb" />

### Add To Cart Page

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2858d369-7213-4141-a53f-4bdc9ddbe6ae" />

### Why Choose Croma Mart Section

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f25261f3-46ed-4257-842c-5d712997132d" />

### Contact Us Section

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/62f713eb-189b-4128-b21a-1e306d87a258" />


## Features

### Product Management
- Product listing with **image, name, price, category, and stock**
- Product details page with **description and quantity selector**
- **Stock-aware purchasing** to prevent over-ordering

### Shopping Cart
- Add products to cart
- Increase and decrease product quantity
- Remove items from cart
- **Automatic total price calculation**
- **Per-item subtotal calculation**
- Cart sidebar with smooth animations

### Authentication
- User **Sign Up and Sign In**
- Session persistence using **LocalStorage**
- Per-user cart data handling
- Logout functionality

### Filtering and Navigation
- **Category-based filtering**
- **Price range filtering**
- Responsive product grid
- Smooth routing with **React Router DOM**

### Persistence and Checkout
- Cart data stored in **LocalStorage**
- Checkout functionality with stock update
- Order success confirmation page
- **Toast notifications** for user feedback

---

## Tech Stack

- **Frontend:** ReactJS (Vite)
- **State Management:** React Context API
- **Routing:** React Router DOM
- **Styling:** Tailwind CSS
- **Icons:** React Icons, Font Awesome
- **Notifications:** React Toastify
- **Storage:** Browser LocalStorage

---
## 📁 Project Structure

```bash
src/
│
├── components/
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── Sidebar.jsx
│   ├── Product.jsx
│   ├── CartItem.jsx
│   ├── CategoryFilter.jsx
│   └── PriceFilter.jsx
│
├── contexts/
│   ├── AuthContext.jsx
│   ├── CartContext.jsx
│   ├── ProductContext.jsx
│   └── SidebarContext.jsx
│
├── pages/
│   ├── Home.jsx
│   ├── ProductDetails.jsx
│   ├── Signin.jsx
│   ├── Signup.jsx
│   └── OrderSuccess.jsx
│
├── App.jsx
├── main.jsx
└── index.css
```
##  Getting Started

###  Clone the Repository
```bash
git clone https://github.com/IAmBiswabhusan/E-COMMERCE-WEBSITE-React.git
cd E-COMMERCE-WEBSITE-React
```

###  Install Dependencies
```bash
npm install
```
###  Run in Development Mode
```bash
npm run dev
```
###  Build for Production 
```bash
npm run build
```
### Preview Production Build
```bash
npm run preview
```
##  Application Flow

- User visits the **Home Page**
- Browses products using **Category** and **Price Filters**
- Opens the **Product Details** page
- Adds items to the **Cart**
- Updates quantity or removes products
- **Signs up** or **Signs in**
- Proceeds to **Checkout**
- Views the **Order Success** confirmation page

---

##  UI & UX Highlights

-  Dark-themed modern interface  
-  Smooth transitions and hover effects  
-  Responsive layout for desktop and mobile  
-  Intuitive cart and checkout experience  
 

---

##  Author

**Srikanth BN**  
Aspiring Developer & React Enthusiast  

 Email: `srikanthbhagyanagaraj@gmail.com`  
🔗 
