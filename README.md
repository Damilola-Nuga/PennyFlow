# 🏦 PennyFlow - A Simple Finance Tracker  


![PennyFlow Screenshot](image.png)


## 📌 Introduction  

PennyFlow is a lightweight finance tracking app designed for simplicity and ease of use. Many financial tools are either too complex or too basic—PennyFlow strikes a balance by offering a clean, intuitive experience without unnecessary features.  

The goal was to build a web app that feels **smooth and responsive like a SPA (Single Page Application)** while leveraging the **power and simplicity of Django, HTMX, Tailwind CSS, and Daisy UI** in a **Multi-Page Application (MPA)** structure.  

👉 **Live Project:** [YouTube Demo Link](https://www.youtube.com/watch?v=xOtp5pekbEA)  
👉 **GitHub Repository:** [PennyFlow Repo](https://github.com/Damilola-Nuga/PennyFlow/tree/main)  

---

## 🚀 Features  

✅ **Transaction Management** – Add, edit, and delete income and expense entries.  
✅ **Real-Time Updates** – Instant UI updates using HTMX without full page reloads.  
✅ **Intuitive UI** – A clean, mobile-responsive interface with Tailwind CSS & Daisy UI.  
✅ **Dynamic Filtering** – Search and filter transactions easily.  
✅ **Net Income Calculation** – See an automatic breakdown of your financials.  

---

## 🎯 Why PennyFlow?  

I built PennyFlow because I needed a **simple yet effective** way to track finances without the clutter of traditional finance apps. Instead of relying on heavy frontend frameworks, I used **HTMX** to create a **dynamic user experience** while keeping the app as lightweight as possible.  

One of the biggest challenges was integrating **HTMX with Tailwind CSS and Daisy UI** to create a seamless, interactive experience. The goal was to make the app feel like a **SPA**, even though it was built as a **Multi-Page Application (MPA)** using Django. Achieving this required careful structuring of partials, using HTMX for dynamic content loading, and ensuring a **consistent user interface with minimal JavaScript**.  

The result? A **fast, elegant, and user-friendly finance tracker** that feels modern but remains simple at its core.  

---

## 🛠️ Tech Stack  

| **Technology**  | **Usage** |
|----------------|-----------|
| Django        | Backend & Server-Side Logic |
| HTMX          | Enhancing Interactivity Without JavaScript |
| Tailwind CSS  | Styling & Responsive UI |
| Daisy UI      | Prebuilt UI Components for Faster Development |
| SQLite        | Default Lightweight Database |
| Django Forms  | Handling Transaction Input & Validation |

---

## 🔧 Installation  

Follow these steps to set up PennyFlow locally:  

### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/yourusername/pennyflow.git
cd pennyflow
```

### **2️⃣ Set Up a Virtual Environment**  
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **4️⃣ Run Database Migrations**  
```bash
python manage.py migrate
```

### **5️⃣ Start the Development Server**  
```bash
python manage.py runserver
```
Visit **http://127.0.0.1:8000/** in your browser to use PennyFlow locally. 🚀  

---

## 🎮 Usage  

Once the server is running:  

1️⃣ **Add Transactions:** Click the "Add Transaction" button and enter the details.  
2️⃣ **View Financial Summary:** The net income is automatically calculated.  
3️⃣ **Filter Transactions:** Search for specific entries using the filter bar.  
4️⃣ **Mobile Friendly:** The UI is fully responsive and works seamlessly on all devices.  

---

## 🔥 Overcoming the Biggest Technical Challenge  

One of the most challenging aspects of building PennyFlow was integrating **HTMX with Tailwind CSS and Daisy UI** to create a seamless, responsive interface.  

The challenge was making PennyFlow feel like a **SPA**, even though it was built as an **MPA** using Django. This required:  

- Structuring **partials** properly to ensure HTMX could handle updates dynamically.  
- Using **Daisy UI components** to speed up development while maintaining a clean, modern look.  
- Ensuring that **HTMX requests updated only the necessary parts of the page**, reducing unnecessary reloads.  

Initially, I ran into issues with **HTMX not updating elements correctly**, and some **Tailwind styles not applying dynamically**. After experimenting with different approaches, tweaking the structure, and carefully applying **HTMX attributes**, I was able to create an experience that feels smooth and modern—without using JavaScript-heavy frameworks.  

---

## 🎓 Lessons Learned from PennyFlow  

This project reinforced several key lessons:  

- **Efficient UI Design Matters** – Keeping things simple while ensuring interactivity is key.  
- **HTMX is a Game-Changer** – It provides the interactivity of a modern frontend without the complexity of a full JS framework.  
- **Balancing Features and Simplicity** – Many finance apps are bloated with features. PennyFlow taught me the importance of keeping things **clean, fast, and user-friendly**.  

Looking ahead, I plan to add:  

- **🔒 User Authentication** – To allow users to save and manage their own transactions.  
- **📊 Data Visualization** – Graphs & charts for better insights.  
- **📂 Export Data** – CSV/Excel export functionality.  
- **📅 Recurring Transactions** – Automate monthly expenses.  

---

## 🛠️ Contributing  

Want to improve PennyFlow? Feel free to contribute! 🚀  

### **📌 Steps to Contribute:**  
1. **Fork the Repository** – Click the "Fork" button on GitHub.  
2. **Clone Your Fork** – Download the forked repo:  
   ```bash
   git clone https://github.com/yourusername/pennyflow.git
   cd pennyflow
   ```
3. **Create a Feature Branch** – Make changes in a new branch:  
   ```bash
   git checkout -b feature-new-idea
   ```
4. **Commit & Push** – Save and upload your changes:  
   ```bash
   git commit -m "Added a new feature"
   git push origin feature-new-idea
   ```
5. **Submit a Pull Request** – Go to GitHub and open a PR!  

---

## 🔗 Related Projects  

If you like **PennyFlow**, you may also find these projects useful:  

- [Bagels](https://github.com/EnhancedJax/Bagels) – a TUI application where you can track and analyse your money flow, with convenience oriented features and a complete interface.  
- [Expenso](https://github.com/Spikeysanju/Expenso) – A Simple Expense Tracker App 📱 built to demonstrate the use of modern android architecture component with MVVM Architecture .  

---

## 💬 Get in Touch  

💻 **GitHub:** [My Profile](https://github.com/Damilola-Nuga)  
🔗 **LinkedIn:** [My LinkedIn](https://www.linkedin.com/in/damilola-onanuga-73a93a214/)  
  