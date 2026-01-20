1️⃣ System Scope — What the system DOES (non-negotiable)  
Core modules (MVP)  
User Management  
Roles: Owner, Staff  
Secure login  
Customer Management  
Customer profiles  
Contact details  
Purchase history  
Sales Management  
Sales entry (date, product, quantity, price)  
Automatic totals  
Daily / monthly reports  
Inventory Management  
Product list  
Stock levels  
Low-stock alerts  
Reporting Dashboard  
Total sales  
Best-selling products  
Stock status  
👉 Anything beyond this is optional and added later.  
2️⃣ Technical Architecture — Exact stack  
A. Frontend (User Interface)  
Web-based application (mobile-friendly)  
Accessed via browser (phone, tablet, PC)  
No installation required  
Reason: Low-end devices + simplicity.  
B. WAN Connectivity  
Internet via:  
4G/5G mobile data  
Fiber (where available)  
Starlink (backup / rural areas)  
WAN role:  
Connects every business location to the same cloud system in real time.  
C. Cloud Backend (Core of the system)  
Cloud Provider (choose ONE):  
AWS (preferred)  
Azure  
Google Cloud  
Services used:  
Cloud Application Server → runs the system logic  
Cloud Database → stores business data  
Cloud Storage → stores receipts/documents  
Identity & Access Control → user authentication  
3️⃣ Data Model — What is stored (simple & clean)  
Main tables  
Users (id, name, role, business_id)  
Businesses (id, name, location)  
Customers (id, name, phone, business_id)  
Products (id, name, price, stock)  
Sales (id, product_id, quantity, date, user_id)  
👉 This is enough to run a real business.  
4️⃣ Data Flow — How it works in real life  
Staff logs in from phone  
Records a sale  
Data travels via WAN (Internet)  
Cloud server processes it  
Database updates instantly  
Owner sees updated dashboard anywhere  
Flow:  
User → WAN → Cloud App → Cloud Database → Dashboard  
5️⃣ Security & Reliability (minimum required)  
Password-based authentication  
Role-based access (staff ≠ owner)  
Encrypted cloud storage  
Automatic daily backups  
6️⃣ Implementation Plan — Step by step  
Phase 1: Setup  
Select cloud provider  
Deploy backend & database  
Configure security  
Phase 2: Build  
Develop web interface  
Implement core modules  
Connect frontend to backend  
Phase 3: Deployment  
Connect businesses via Internet  
Create user accounts  
Migrate paper data  
Phase 4: Training  
1–2 hour basic training  
Focus on sales & inventory only  
7️⃣ What MUST stop immediately  
Paper notebooks  
Sales tracking on personal phones  
No backups  
Manual inventory estimation  
8️⃣ Risks & Controls (realistic)  
Internet down → mobile data / Starlink  
User resistance → keep UI minimal  
Data misuse → role-based access  
  
START THE SYSTEM
