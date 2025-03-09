# sauce-demo-test-automation
🚀 Sauce Demo Test Automation
Automated Login Testing for SauceDemo using Selenium & Java

📌 Project Overview
This project automates the login functionality of SauceDemo using Selenium WebDriver in Java. It includes:
✅ Positive Test Cases (Valid credentials)
✅ Negative Test Cases (Invalid credentials, empty fields)
✅ Exception Handling for stability
✅ Assertions to verify login behavior
✅ Detailed Logging & Reports

🛠 Tech Stack & Tools
Language: Java
Automation Framework: Selenium WebDriver
Testing Framework: JUnit/TestNG
Build Tool: Maven
Logging: SLF4J & Log4j
Browser: Chrome (via WebDriver)
⚡ Installation & Setup
1️⃣ Clone Repository
sh
Copy
Edit
git clone https://github.com/yourusername/sauce-demo-test-automation.git
cd sauce-demo-test-automation
2️⃣ Setup Dependencies
Make sure Java (JDK 11+) and Maven are installed. Then, install dependencies:

sh
Copy
Edit
mvn clean install
3️⃣ Run Tests
For JUnit:

sh
Copy
Edit
mvn test
For TestNG:

sh
Copy
Edit
mvn test -Dsurefire.suiteXmlFiles=testng.xml
🔍 Test Scenarios
Test Case	Description	Expected Result
✅ Valid Login	Correct username & password	Successful login
❌ Invalid Username	Wrong username, correct password	Error message
❌ Invalid Password	Correct username, wrong password	Error message
❌ Empty Fields	No input in fields	Error message
📸 Screenshots
Add relevant screenshots here!

🛠 Troubleshooting
SLF4J Warning? Add an SLF4J binding (e.g., log4j-slf4j-impl).
WebDriver Version Issue? Ensure the latest ChromeDriver is installed.

📌 Contributing
💡 Found an issue? Want to improve the tests? Feel free to open a PR!

📜 License
This project is open-source under the MIT License.

This README is clear, structured, and professional. Let me know if you want any modifications! 🚀🔥












Search
