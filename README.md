
---

# APDS7311_POE_YouMakeMyCSharp(Team CDJKY)

APDS7311_POE_YouMakeMyCSharp(TeamCDJKY_APDS7311_POE) is an international payment system designed to streamline payment processing for a bank's customers and employees. The system enables customers to initiate payments securely, while employees verify and submit these payments via SWIFT. Built with a robust frontend-backend architecture, this project emphasizes security, scalability, and usability.

---

## Team Members (aka Team CDJKY)

- **ST10090916** - Cian Brink  
- **ST10090943** - Dylan Pather  
- **ST10059881** - Kayur Betchu  
- **ST10048945** - Joshua Reddy  
- **ST10061733** - Yuvaan Pather  

---

## Features

### Customer Features:
- **User Authentication**: Secure login for customers using ID number and password.
- **Payment Processing**: Customers can make international payments by providing amount, currency, payee account information, and SWIFT codes.
- **Real-Time Validation**: Input fields validate data in real-time for accuracy.

### Employee Features:
- **Employee Authentication**: Employees log in securely using their credentials.
- **Payment Verification**: Employees verify customer payments for accuracy and completeness before submission.
- **Payment Submission to SWIFT**: Verified payments are submitted to SWIFT for processing.
- **Employee/Customer Management**: Employees can create new employee and customer accounts.

### Security Features:
- **Password Hashing and Salting**: Ensures secure storage of user credentials.
- **SSL Encryption**: Protects all traffic between the client and server.
- **Validation and Sanitization**: Prevents malicious inputs using regular expressions and robust backend checks.

---

## Links

- **GitHub Repository**: [CDKJY_APDS7311_POE](https://github.com/ST10090916-CianBrink/CDKJY_APDS7311_POE)
- **Project Overview on YouTube**: [YouTube Video](https://youtu.be/GpTI8hoV4f8)

---

## Getting Started

### Prerequisites
- **Frontend**: Node.js (latest version), npm/yarn
- **Backend**: Node.js, npm, MongoDB
- **SSL Certificates**: Generated locally or via a trusted authority
- **SonarQube/SonarCloud**: For static code analysis

---

### Installation

#### 1. Clone the Repository:
```bash
git clone https://github.com/ST10090916-CianBrink/CDKJY_APDS7311_POE.git
cd apds_poe2_final_cdjky
```

#### 2. Backend Setup:
```bash
cd backend
npm install
```
- Ensure MongoDB is running locally or in the cloud.
- Add a `.env` file with the following variables:
  ```env
  MONGO_URI=<Your MongoDB Connection String>
  PORT=5000
  ```

#### 3. Frontend Setup:
```bash
cd ../frontend
npm install
npm start
```

#### 4. Project Execution:
```bash
npm run dev
```
---

## Usage

### **Customer Flow**
1. Customers log in using their ID number and password.
2. They can initiate payments by filling out the payment form.
3. Payments are securely submitted to the backend for processing.

### **Employee Flow**
1. Employees log in using their credentials.
2. View pending customer payments on the employee dashboard.
3. Verify and submit payments to SWIFT.
4. Create new employee or customer accounts as required.

---

## Roadmap

### Planned Features:
- **Biometric Login**: Fingerprint and face recognition for enhanced security.
- **Audit Logs**: Track all actions performed by employees for better accountability.
- **Multi-Currency Support**: Add support for more currencies and payment options.
- **Advanced Analytics**: Provide data insights for transactions and employee activity.

---

## Technologies Used

- **Frontend**: React.js, CSS3 (styled to match a professional banking system).
- **Backend**: Node.js, Express.js, MongoDB.
- **Security**: SSL, bcrypt, RegEx sanitization.
- **Testing**: Integrated with CircleCI and SonarCloud for continuous integration and static code analysis.

---

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and submit a pull request.

---

## Issues and Bug Reporting

If you encounter any issues, please create an issue in the repository. Include detailed information such as:
- Steps to reproduce the issue.
- Expected vs. actual behavior.
- Screenshots (if applicable).

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details. 

---

### Thank You!
**Innovative Technology Brought To You By:**  
Cian, Dylan, Kayur, Joshua, and Yuvaan! 🎉

--- 
