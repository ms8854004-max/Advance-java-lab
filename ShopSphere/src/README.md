# ShopSphere - Online E-Commerce & Inventory Management System
### Advanced Java Lab Project (5th Semester)

**Developer:** Vishal saraswat
**Roll No:** 24EGJCS644
**Course:** B.Tech Computer Science & Engineering / AI & DS (5th Sem)  
**College:** Global Institute of Technology (GIT), Jaipur  
**University:** Rajasthan Technical University (RTU), Kota  

---

## What is ShopSphere?

ShopSphere is an e-commerce project built for my 5th Semester Advanced Java Lab. 

Instead of making just a standard website or just a desktop form, I combined both:
1. **Web Store (Tomcat Web Application):** A full web application using Servlets and JSP where customers can browse products, manage their cart, and place orders. It also includes an admin panel to manage products and track orders.
2. **Desktop Inventory Tool (Java Swing GUI):** A standalone desktop app (`SwingInventoryViewer.java`) made for back-office or shop managers. It connects directly to the same MySQL database via JDBC, displays current stock levels in a table, and allows one-click restocking.

Both the website and desktop application run simultaneously on the same MySQL database, so whenever a customer buys an item online or stock is updated from the desktop app, the changes reflect in real time.
