# Welcome to Electricity Bill Management System
The Electricity Bill Management System is a JavaFX-based application designed to 
simplify and automate electricity billing operations. It allows users to generate
bills using consumer details and meter readings, apply dynamic discounts, fines 
for late payments and adjustable tax rates and update the payment status of each
bill. All billing data is stored in a structured file, making it lightweight and 
easy to manage. The system includes separate Java classes such as Payment, 
Discount and Fine, each following Object-Oriented Programming (OOP) principles to
ensure modularity and maintainability. The user interface is built with JavaFX 
components like ComboBoxes, TextFields and Buttons which provides an intuitive 
and interactive experience for managing billing records and viewing revenue 
updates efficiently.

## Features
- Bill generation using user CNIC, name, address, category and meter readings.
- Dynamic application of discounts, fines (for late payments), and customizable tax rates.
- Payment status update functionality with real-time revenue calculation.
- JavaFX-based responsive user interface with ComboBoxes, TextFields, and Buttons.
- Modular OOP structure with separate classes (Payment, Discount, Fine) for clean logic separation.
- Scalable and maintainable codebase suitable for academic or lightweight commercial use.


## Screenshots

<!-- LANDSCAPE IMAGES -->
<div style="width: 100%; text-align: center;">

  <!-- Main Menu -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
       Main Menu <br>
    </div>
    <img src="src/screenshots/mainmenu.png" width="700" height="394">
  </div>

  <!-- Discount -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
      Discount <br>
    </div>
    <img src="src/screenshots/applydiscount.png" width="700" height="394">
  </div>

  <!-- Fine -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
       Fine <br>
    </div>
    <img src="src/screenshots/fine.png" width="700" height="394">
  </div>

  <!-- Pay Bill -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
       Pay Bill <br>
    </div>
    <img src="src/screenshots/paybill.png" width="700" height="394">
  </div>

  <!-- Revenue -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
       Revenue <br>
    </div>
    <img src="src/screenshots/revenue.png" width="700" height="394">
  </div>

  <!-- Update Taxes -->
  <div style="position: relative; width: 700px; margin: 25px auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
     Update Taxes <br>
    </div>
    <img src="src/screenshots/taxes.png" width="700" height="394">
  </div>

</div>

<!-- PORTRAIT IMAGE -->
<div style="width: 100%; text-align: center; margin-top: 40px;">
  <div style="position: relative; width: 420px; margin: 0 auto;">
    <div style="
      position: absolute;
      top: 10px;
      left: 10px;
      background: rgba(0,0,0,0.65);
      color: white;
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 4px;
    ">
       Generate Bill 
      <br>
    </div>
    <img src="src/screenshots/generatebill.png" width="420" height="750">
  </div>
</div>



## Project Structure
```
 ElectrictyBillManagementSystem/            (This is your main project root)
    ├── .idea/                                 (Module-specific IntelliJ configuration)
    │  
    ├── src/                                   (Source code folder)
    │   ├── main/                              (Main source code and resources)
    │   │   ├── java/
    │   │   │   └── com/
    │   │   │       └── example/
    │   │   │           └── demo4/
    │   │   │               ├── ApplyDiscountController.java
    │   │   │               ├── ApplyLateFineController.java
    │   │   │               ├── CallGenerateBill.java
    │   │   │               ├── Category.java
    │   │   │               ├── Discount.java
    │   │   │               ├── ElectricityBillSystem.java
    │   │   │               ├── Fine.java
    │   │   │               ├── GenerateBill.java
    │   │   │               ├── GenerateBillController.java
    │   │   │               ├── HelloApplication.java
    │   │   │               ├── HelloController.java
    │   │   │               ├── PayBillController.java
    │   │   │               ├── Payment.java
    │   │   │               ├── RevenueStatisticsController.java
    │   │   │               ├── Taxes.java
    │   │   │               └── TaxesController.java
    │   │   └── module-info.java
    │   │
    │   └── resources/                         (FXML and other resources)
    │
    ├── screenshots/                           (Your screenshots folder)
    ├── Readme.md                              (Your main Readme file)
    ├── .gitignore                             (Git ignore file for project)
    ├── mvnw                                   (Maven Wrapper script for Linux/macOS)
    ├── mvnw.cmd                               (Maven Wrapper script for Windows)
    └── pom.xml                                (Maven Project Object Model file)
 ```

## Technologies Used
- **Language**: Java 17
- **Framework**: JavaFX
- **Styling**: JavaFX
- **Build Tool**: Maven
- **OOP Concepts**: Encapsulation, Association, Inheritance, Enumeration

## Contributing
I welcome contributions to enhance Electrity Bill Management System. Here's how you can help:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m "Add your message"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request with a description of your changes.

Please ensure your code follows the existing style.

## Contact
- **Author**: Najmul Arifeen
- **GitHub**: [https://github.com/najmularifeen](https://github.com/najmularifeen)
