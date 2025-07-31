# 🌱 Paradise Nursery

**Welcome to Paradise Nursery**, an e-commerce platform for plant enthusiasts!  
This project is designed to provide users with a seamless shopping experience for a variety of plants, including:

- Air-purifying  
- Aromatic  
- Insect-repellent  
- Medicinal  
- Low-maintenance  

Whether you're a seasoned gardener or just starting your green journey, **Paradise Nursery** has something for everyone.

---

## ✨ Features

- **Landing Page**: Visually appealing introduction to Paradise Nursery.
- **Product Categories**: Browse plants by category — *Air Purifying*, *Aromatic Fragrant*, *Medicinal*, and more.
- **Shopping Cart**: Add, remove, and update quantities of plants in your cart.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Redux Integration**: Efficient state management for cart functionality.
- **Checkout Placeholder**: Ready for future checkout system integration.

---

## 🛠️ Technologies Used

- **Frontend**: React.js  
- **State Management**: Redux Toolkit  
- **Styling**: CSS  
- **Build Tool**: Vite  
- **Deployment**: GitHub Pages  

---

## 🚀 Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Carlos-J-Guevara/e-plantShopping.git
   cd e-plantShopping
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start the development server:**

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to:  
   👉 [http://localhost:5173](http://localhost:5173)

---

## 🌐 Deployment

This project is deployed using **GitHub Pages**.

To deploy your own version:

1. **Build the project:**

   ```bash
   npm run build
   ```

2. **Deploy the `dist/` folder** using the `gh-pages` package:

   ```bash
   npm install --save-dev gh-pages
   ```

3. **Add the following scripts to `package.json`:**

   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

4. **Deploy with:**

   ```bash
   npm run deploy
   ```

---

## 📂 Project Structure

The following is a suggested directory structure:

```
e-plantShopping/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── redux/
│   └── App.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## 🔮 Future Enhancements

- ✅ **Checkout Functionality**: Integrate a payment gateway.
- 🔒 **User Authentication**: Add login and signup features.
- ❤️ **Wishlist**: Allow users to save favorite plants.
- 🌟 **Reviews**: Let users leave reviews for products.

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. **Fork** the repository.
2. **Create a new branch:**

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Commit your changes:**

   ```bash
   git commit -m "Add your message"
   ```

4. **Push to your branch:**

   ```bash
   git push origin feature/your-feature-name
   ```

5. **Open a pull request** to propose your changes.

---

## 📄 License

This project is licensed under the **Apache License 2.0**.  
See the [LICENSE](LICENSE) file for more information.

---

## 🙌 Acknowledgments

- Inspired by the beauty of nature and the importance of sustainability.
- Images sourced from [Pixabay](https://pixabay.com) and [Unsplash](https://unsplash.com).
- Thank you for visiting **Paradise Nursery**! 🌿