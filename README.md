
👩‍💼 Employee Management CRUD Application  
A full-stack CRUD web application for managing employee data.  
Built using **ASP.NET Core Web API (Server)** and **ASP.NET Core MVC (Client)** inside a single Visual Studio solution.

🧾 Project Description  
This solution is divided into two projects:

- **Server**: ASP.NET Core Web API for handling all CRUD operations using EF Core and LocalDB.  
- **Client**: ASP.NET Core MVC application to interact with the API using forms, views, and Bootstrap for responsive design.

🟢 Both projects run together automatically.  
No extra SDK installation, SQL Server configuration, or terminal setup is needed.

---

▶️ Steps to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HabibaSCreations/EmployeeCrudSolution.git
   ```

2. **Open the solution in Visual Studio:**
   - File → Open → Project/Solution → `EmployeeCrudSolution.sln`

3. **Set startup projects:**
   - Right-click on the solution → *Set Startup Projects...*
   - Choose *Multiple startup projects*
   - Set both `Server` and `Client` projects to **Start**

4. **Setup Database (Using Package Manager Console):**
   - Open **PMC** (Tools → NuGet Package Manager → Package Manager Console)
   - Set **Default Project** to `Server`
   - Run:
     ```powershell
     Add-Migration InitialCreate
     Update-Database
     ```

📝 *If a database with the same name already exists, change the connection string in `appsettings.json` before running.*

5. **Run the application:**
   - Press `F5` or click the **Run** button  
   - Both the Web API and MVC client will launch automatically

---

🛠️ Technologies Used

- ASP.NET Core Web API  
- ASP.NET Core MVC  
- Entity Framework Core  
- SQL Server LocalDB  
- Bootstrap 5

---

🔗 Navigation Bar Includes:

👩‍💼 Brand: **"My Employee"**

Menu Links:
- Home  
- Employee List  
- Create Employee  
- Responsive Hamburger Menu for smaller devices

---

✅ Core Features

- View all employees  
- Add a new employee  
- Edit employee information  
- Delete employee records  
- View single employee details  
- Responsive and user-friendly UI with Bootstrap

---

🧑‍💻 Author

**Habiba Anjum**  
GitHub: [https://github.com/HabibaSCreations](https://github.com/HabibaSCreations)

Email:habibaanjum9799@gmail.com

---

📝 License  
This project is intended for **learning and educational purposes only**.
