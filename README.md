# Email Application

## Overview

The **Email Application** is a Java-based console application designed to create and manage employee email accounts for a company. This project demonstrates fundamental object-oriented programming principles, such as encapsulation, inheritance, and polymorphism.

## Features

- Create email accounts for new employees.
- Set and change mailbox capacity.
- Generate random passwords for email accounts.
- Set and retrieve alternative email addresses.
- Display employee email information.

## Prerequisites

- Java Development Kit (JDK) installed.
- A Java IDE or text editor (e.g., IntelliJ, Eclipse, VSCode).

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/email-application.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd email-application
   ```

3. **Compile the Java files:**
   ```bash
   javac emailapp/EmailApp.java emailapp/Email.java
   ```

4. **Run the application:**
   ```bash
   java emailapp.EmailApp
   ```

## Usage

Upon running the application, you will be prompted to enter the department code for the employee. The application will then generate an email address and a random password, and display this information along with the mailbox capacity.

### Example

```plaintext
EMAIL CREATED: Naruto Uzumaki
DEPARTMENT CODES:
1 for Sales
2 for Development
3 for Accounting
0 for None
Enter Department code: 2
Department: dev
Your password is: A1B2C3D4
Your email is: naruto.uzumaki@dev.anycompany.com
DISPLAY NAME: Naruto Uzumaki
COMPANY EMAIL: naruto.uzumaki@dev.anycompany.com
MAILBOX CAPACITY: 500mb
```

## Classes and Methods

### EmailApp.java

- **EmailApp:** Contains the `main` method which serves as the entry point of the application.

### Email.java

- **Email:** Handles the creation of email accounts and includes the following methods:
  - `Email(String firstName, String lastName)`: Constructor that initializes the email account.
  - `private String setDepartment()`: Prompts user for department code and sets the department.
  - `private String randomPassword(int length)`: Generates a random password of specified length.
  - `public void setMailboxCapacity(int capacity)`: Sets the mailbox capacity.
  - `public void setAlternativeEmail(String altEmail)`: Sets an alternative email address.
  - `public void changePassword(String password)`: Changes the account password.
  - `public int getMailboxCapacity()`: Returns the mailbox capacity.
  - `public String getAlternativeEmail()`: Returns the alternative email address.
  - `public String getPassword()`: Returns the account password.
  - `public String showInfo()`: Displays the employee's name, email address, and mailbox capacity.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes you would like to make.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact [sakshamkothari11@gmail.com].

---

This README provides a comprehensive overview of the project, setup instructions, usage examples, and information about the classes and methods used in the application.
