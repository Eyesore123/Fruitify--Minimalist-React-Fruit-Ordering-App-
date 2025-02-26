# 🌟 **Fruitify - Your Ultimate Fruit Ordering App** 🍎🍇🍓  

### 🛒 **A Minimalist and Elegant Online Fruit Shopping Experience!**

Fruitify is a sleek, feature-packed React-based application designed for ordering fresh fruits. With Firebase authentication, a modern UI, seamless animations, and robust filtering and sorting features, Fruitify ensures a smooth and delightful shopping experience.  

---

## 🚀 **Key Features**  
✨ **Add to Cart** – Add your favorite fruits with a single click.  
✨ **Product Filtering & Sorting** – Quickly find and sort the best options to suit your taste.  
✨ **Pagination** – Browse products effortlessly across multiple pages.  
✨ **User Authentication** – Secure login and registration for personalized experiences.  
✨ **Checkout System** – Complete your orders securely.  
✨ **Modern UI & Animations** – Eye-catching design with smooth interactions.  

---

## 🛠️ **Tech Stack**

**Built with love using:**  
- ⚛️ React.js  
- 🛠️ Redux Toolkit  
- 🎨 ReactStrap & CSS  
- 🔥 Firebase Authentication  
- 🛍️ Bootstrap & React-Toastify  
- 🔗 React Router Dom  
- 💫 Framer Motion  

---

## 🖥️ **Website Preview**

[✨ Not Available Right Now ✨]

---

## 🏗️ **Getting Started**

Follow these steps to set up the project locally:

## 🔥 Firebase Setup

To run Fruitify locally, you need to set up Firebase authentication. Follow these steps:

1. **Create a Firebase Project**
   - Go to [Firebase Console](https://console.firebase.google.com/).
   - Click **"Create a Project"** and follow the setup steps.

2. **Get Your Firebase Config Object**
   - Inside your Firebase project, navigate to **Project Settings** > **General**.
   - Scroll down to **"Your apps"** and click **"Add app"** (Choose Web).
   - Register the app, and Firebase will generate a config object like this:

   ```javascript
   const firebaseConfig = {
     apiKey: "YOUR_API_KEY",
     authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
     projectId: "YOUR_PROJECT_ID",
     storageBucket: "YOUR_PROJECT_ID.appspot.com",
     messagingSenderId: "YOUR_SENDER_ID",
     appId: "YOUR_APP_ID"
   };

3. **Create a Firebase Config File**

*   Inside your project, create a new file named firebase.config.js in the src folder.
    
*   Paste your Firebase configuration inside:
    

    ```javascript
    import { initializeApp } from "firebase/app";
    
    const firebaseConfig = {
    
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_PROJECT_ID.appspot.com",
    messagingSenderId: "YOUR_SENDER_ID",
    appId: "YOUR_APP_ID"
    
    };
    
    const app = initializeApp(firebaseConfig);
    
    export default app;

>⚠️ Alternative Method: You can store Firebase credentials in a .env file instead of firebase.config.js.  

- Create a .env file in your root folder and add:
    ```ini
    REACT_APP_FIREBASE_API_KEY=YOUR_API_KEY
   REACT_APP_FIREBASE_AUTH_DOMAIN=YOUR_PROJECT_ID.firebaseapp.com
   REACT_APP_FIREBASE_PROJECT_ID=YOUR_PROJECT_ID
   REACT_APP_FIREBASE_STORAGE_BUCKET=YOUR_PROJECT_ID.appspot.com
   REACT_APP_FIREBASE_MESSAGING_SENDER_ID=YOUR_SENDER_ID
   REACT_APP_FIREBASE_APP_ID=YOUR_APP_ID

- Update firebase.config.js:

    ```javascript
    import { initializeApp } from "firebase/app";
    const firebaseConfig = {
      apiKey: process.env.REACT_APP_FIREBASE_API_KEY,
      authDomain: process.env.REACT_APP_FIREBASE_AUTH_DOMAIN,
      projectId: process.env.REACT_APP_FIREBASE_PROJECT_ID,
      storageBucket: process.env.REACT_APP_FIREBASE_STORAGE_BUCKET,
      messagingSenderId: process.env.REACT_APP_FIREBASE_MESSAGING_SENDER_ID,
      appId: process.env.REACT_APP_FIREBASE_APP_ID
    };

    const app = initializeApp(firebaseConfig);
    
    export default app;



4. **Run the Development Server**  
Now, you can start the local server:

```
npm run dev

```

#### **2️⃣ Mention Firebase in the "Getting Started" Section**

Before step **"npm run dev"**, add a note:


>⚠️ Note: Before running the development server, make sure you have set up Firebase as described in the [Firebase Setup](#firebase-setup) section.




### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/Muhammad-waqas1/Fruitify--Minimalist-React-Fruit-Ordering-App-.git
```

### 2️⃣ Navigate to Project Directory
```bash
cd fruitify
```
### 3️⃣ Install Dependencies
```bash
npm install
```
### 4️⃣ Start the Development Server
```bash
npm run dev
```
### 🌐 Live Deployment
Deploy this project with a single command:

``` bash
npm run deploy
```
## 📚 Installation Guide
Install Fruitify using npm:
```bash
npm install fruitify
cd fruitify
```

---------------------------
# 🎉 **Why Choose Fruitify?**

🍉 A **minimalist UI** focused on usability. <br>
🍋 Fast **product search, filter, and pagination**. <br>
🍒 Built with **scalable technologies** for maximum performance. <br>
🍍 Perfect for learning or deploying a modern e-commerce app. 

---------------------------


# 🤝 **Contributing Guidelines**
------------------------------

We welcome contributions from the community! Follow the steps below to get started:

1.  **Fork the Repository**  
Click the "Fork" button at the top-right of this repository to create your copy.
    
2.  **Clone Your Forked Repository**  
    ```bash
    clone https://github.com/Muhammad-waqas1/Fruitify--Minimalist-React-Fruit-Ordering-App-.git
    ```
    
4.  **Create a Branch**  
    Create a branch for your feature or bug fix:  
    ```bash
    git checkout -b feature-name
    ```
    
5.  **Make Changes**  
Implement your feature or bug fix. Please ensure the code is clean and adheres to the existing code style.
    
6.  **Test Your Changes**  
Run the app locally to ensure your changes work as expected:  
    ```bash
    npm run dev
    ```
    
7.  **Commit Your Changes**  
  Write a clear and concise commit message:  
    ```bash
    git commit -m "Add: Feature description"
    ```
    
8.  **Push to Your Branch**  
    ```bash
    git push origin feature-name
    ```
    
9.  **Submit a Pull Request**  
    Go to the original repository, click on "Pull Requests," and submit your PR. Describe your changes and link any relevant issues.
    

### 🛡️ License

This project is open-source and available under the [MIT License](LICENSE).

>_⭐ If you like this project, don't forget to give it a star! Your support is much appreciated! ✨_
