# Electricity Bill Management System

The **Electricity Bill Management System** is a JavaFX-based application designed to simplify and automate electricity billing operations. It allows users to generate bills using consumer details and meter readings, apply dynamic discounts, fines for late payments, and adjustable tax rates, and update the payment status of each bill. 

All billing data is stored in a structured file, making it lightweight and easy to manage. The system includes separate Java classes such as `Payment`, `Discount`, and `Fine`, each following Object-Oriented Programming (OOP) principles to ensure modularity and maintainability. The user interface is built with JavaFX components like ComboBoxes, TextFields, and Buttons, providing an intuitive and interactive experience for managing billing records and viewing revenue updates efficiently.

## Features

* **Bill Generation:** Create bills using user CNIC, name, address, category, and meter readings.
* **Dynamic Calculations:** Application of discounts, fines (for late payments), and customizable tax rates.
* **Payment Tracking:** Status update functionality with real-time revenue calculation.
* **Responsive UI:** JavaFX-based interface with intuitive controls.
* **OOP Design:** Modular structure with separate classes (`Payment`, `Discount`, `Fine`) for clean logic separation.
* **Scalability:** Maintainable codebase suitable for academic or lightweight commercial use.

## Screenshots

### Main Menu
<img src="src/screenshots/mainmenu.png" width="700" alt="Main Menu">

### Discount
<img src="src/screenshots/applydiscount.png" width="700" alt="Apply Discount">

### Fine
<img src="src/screenshots/fine.png" width="700" alt="Apply Fine">

### Pay Bill
<img src="src/screenshots/paybill.png" width="700" alt="Pay Bill">

### Revenue
<img src="src/screenshots/revenue.png" width="700" alt="Revenue">

### Update Taxes
<img src="src/screenshots/taxes.png" width="700" alt="Update Taxes">

### Generate Bill
<img src="src/screenshots/generatebill.png" width="420" alt="Generate Bill">

<br>

## Project Structure

```text
ElectrictyBillManagementSystem/             (This is your main project root)
    ├── .idea/                              (Module-specific IntelliJ configuration)
    ├── src/                                (Source code folder)
    │   ├── main/                           (Main source code and resources)
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
    │   └── resources/                      (FXML and other resources)
    │
    ├── screenshots/                        (Screenshots folder)
    ├── Readme.md                           (Your main Readme file)
    ├── .gitignore                          (Git ignore file)
    ├── mvnw                                (Maven Wrapper script for Linux/macOS)
    ├── mvnw.cmd                            (Maven Wrapper script for Windows)
    └── pom.xml                             (Maven Project Object Model file)
```
## Technologies Used
- **Language:** Java 17
- **Framework:** JavaFX
- **Styling:** JavaFX CSS
- **Build Tool:** Maven
- **OOP Concepts:** Encapsulation, Association, Inheritance, Enumeration

## Running the Project

### Requirements
- Java JDK installed (version 17 or higher recommended)
- JavaFX library set up in your environment

### Steps to Run

1. **Open a terminal and navigate to the project folder**
   ```bash
   cd path/to/project/src/main/java/com/example/demo4/
   ```
 2. **Compile the application**

> **Note:** Replace `/path/to/javafx/lib` with the actual path where JavaFX is installed on your machine.

```bash
javac --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml HelloApplication.java
```
 3. **Run the application**

```bash 

java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml HelloApplication
```

## Contributing
I welcome contributions to enhance the Electricity Bill Management System. Here's how you can help:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m "Add your message"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request with a description of your changes.

Please ensure your code follows the existing style.

## Contact
- **Author:** Najmul Arifeen
- **GitHub:** [https://github.com/najmularifeen786](https://github.com/najmularifeen786)
