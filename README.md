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

<img width="957" height="413" alt="Explore Product Section" src="https://github.com/user-attachments/assets/170a608b-7737-4362-a467-4295cd3857bc" />


### Filtering Product Based on Category or Price

<img width="932" height="403" alt="Filtering Product Based on Category or Price" src="https://github.com/user-attachments/assets/a94c56f1-7303-4039-a136-306265ddb57d" />


### Add To Cart Page

<img width="625" height="287" alt="Add To Cart Page" src="https://github.com/user-attachments/assets/553c9127-1ee1-4294-954a-7a981c743fce" />


### Why Choose Croma Mart Section

<img width="1869" height="808" alt="Why Choose Croma Mart Section" src="https://github.com/user-attachments/assets/f0337f5a-1e66-4453-9eeb-e7f6e45dd083" />


### Contact Us Section

<img width="1126" height="746" alt="Contact Us Section" src="https://github.com/user-attachments/assets/03643bec-40d8-4aa6-ac7c-f3927a335107" />

### Dashboard data imported from Snowflake integration.

<img width="1151" height="652" alt="Power Bi Dashboard" src="https://github.com/user-attachments/assets/fed2bce8-1556-46af-b9a6-df3f303a7474" />



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
