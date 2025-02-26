# **TMDb API Documentation** 🎬  

This repository contains my **API Documentation Capstone Project**, built using **[Mintlify](https://mintlify.com/)** to provide a clean and interactive developer experience for working with the **TMDb API**.  

## 🚀 **Live Documentation**  
[🔗 View Documentation]_(https://tvc.mintlify.app "View on mintlify")_

---

## 📖 **Project Overview**  
This project is my capstone in API documentation, where I document the **TMDb API** following industry best practices.  

### 🛠 **Project Process**  
1️⃣ **Testing API Endpoints** using **Postman** to understand how the API works.  
2️⃣ **Converting Postman Collections** to an **OpenAPI Specification** file.  
3️⃣ **Editing the OpenAPI Spec** using **Swagger Editor** to refine and structure the API definition.  
4️⃣ **Deploying on Mintlify** using **VS Code**, ensuring a structured and visually appealing developer experience.  

This documentation covers authentication, error handling, best practices, and detailed API references.

---

## 📦 **Installation & Local Setup**  
To run the documentation locally, follow these steps:

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/your-username/tmdb-api-docs.git
cd tmdb-api-docs
```

### 2️⃣ **Install Dependencies**  
Ensure you have Node.js installed, then run:  
```bash
npm install -g mintlify
```

### 3️⃣ **Run the Documentation Locally**  
```bash
mintlify dev
```
Your documentation should now be available at `http://localhost:3000/`.

---

## 📂 **Project Structure**  
```plaintext
starter/
│── api-reference/       # API reference documentation
│── concepts/            # Best practices and guides
│── introduction.mdx     # Overview of TMDb API
│── getting-started.mdx  # Step-by-step guide to begin
│── authentication.mdx   # How to authenticate API requests
│── error-handling.mdx   # Handling errors with the API
│── docs.json            # Configuration for Mintlify navigation
│── README.md            # This file
```

---

## ✨ **Customization**  
You can update the `docs.json` file to modify the sidebar, branding, and navigation.  

To change the **theme color**, update:  
```json
"colors": {
  "primary": "#01B4E4",
  "light": "#90CEA1",
  "dark": "#032541"
}
```

---

## 🤝 **Contributing**  
We welcome contributions! To contribute:  
1. **Fork** the repository  
2. **Create a new branch** (`git checkout -b feature-name`)  
3. **Make changes** and commit (`git commit -m "Added new feature"`)  
4. **Push to GitHub** (`git push origin feature-name`)  
5. **Open a Pull Request**  

---

## 📩 **Support & Contact**  
- **Official TMDb API Docs**: [developer.themoviedb.org/docs](https://developer.themoviedb.org/docs)  
- **Community Forum**: [TMDb Talk](https://www.themoviedb.org/talk)  
- **Email Support**: [support@themoviedb.org](mailto:support@themoviedb.org)  

---

### **📜 License**  
This project is licensed under the [MIT License](LICENSE).