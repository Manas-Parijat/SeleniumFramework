<img width="1842" height="721" alt="image" src="https://github.com/user-attachments/assets/d9001279-4d89-4d44-947a-2f18702b397f" />Selenium Automation Framework (with Java)

**Author - Manas Parijat**

---

## 📌 Overview
This is a **Selenium-based Automation Framework** built using Java, TestNG, and Maven.  
It is designed for **scalable, maintainable, and reusable test automation**, following the **Page Object Model (POM)** pattern with support for advanced reporting and CI/CD integration.

---

## 🛠 Tech Stack
- **Programming Language:** Java (>= 8)
- **Automation Tool:** Selenium WebDriver
- **Test Runner:** TestNG
- **Build Tool:** Maven
- **Logging:** Log4j2
- **Reporting:** Allure Reports / Extent Reports
- **Data Handling:** Apache POI (Excel), Properties File
- **Assertions:** AssertJ / TestNG Assertions
- **Execution:** Local & Remote (Selenoid Docker Grid)

---

## 📂 Project Structure
```
selenium-framework/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── base/          # Base classes (WebDriver setup, config)
│   │   │   ├── pages/         # Page Object classes
│   │   │   ├── utils/         # Utilities (ExcelReader, Logger, etc.)
│   │   └── resources/
│   │       └── config.properties  # Test configuration file
│   ├── test/
│   │   ├── java/
│   │   │   ├── tests/         # Test classes
│   │   │   ├── listeners/     # TestNG listeners
│   │   └── resources/
│── pom.xml                    # Maven dependencies
│── testng.xml                 # TestNG suite configuration
│── README.md                  # Project documentation
```

---

## ⚙️ Setup & Installation

1. **Clone Repository**
   ```bash
   git clone https://github.com/your-repo/selenium-framework.git
   cd selenium-framework
   ```

2. **Install Dependencies**
   ```bash
   mvn clean install
   ```

3. **Configure Properties**
   Update `config.properties` with:
   ```properties
   browser=chrome
   baseUrl=https://example.com
   timeout=20
   ```

4. **Run Tests**
   ```bash
   mvn test -Dsurefire.suiteXmlFiles=testng.xml
   ```

---

## 📊 Reporting

- **Allure Report**
   ```bash
   mvn allure:serve
   ```

- **Extent Report**
  Open `reports/extent-report.html` in a browser.

---

## ✅ Features
- Page Object Model (POM) implementation
- Cross-browser support (Chrome, Firefox, Edge)
- Data-driven testing with Excel (Apache POI)
- Parallel test execution with TestNG
- Thread-safe WebDriver using ThreadLocal
- Centralized logging with Log4j2
- Rich reporting with Allure/Extent Reports
- Execution on **Selenoid Docker Grid** or local machine

---

## 🚀 CI/CD Integration
- Can be integrated with **Jenkins / GitHub Actions / GitLab CI**
- Automated execution on every commit or scheduled job
- Test reports published after build completion

---

## 👨‍💻 Contribution
1. Fork the repository
2. Create a new feature branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to branch (`git push origin feature-branch`)
5. Create a Pull Request

- Java, Selenium, TestNG
- Maven, AssertJ, POM
- Thread Local Support → Thread Safety
- Allure Report
- Excel Sheet for Test Data → Data Provider
- Read the username and password from Properties-
- TestNG, @Test, Before and After Method.
- Cloud Grids
- SonarLint, Java > 8
- Run Local and on Selenoid Integration


<img width="1024" alt="Screenshot 2023-10-31 at 12 27 14 PM" src="https://github.com/PramodDutta/AdvanceSeleniumFrameworkTTA/assets/1409610/02b0ef3b-1165-46cf-8c9d-89e41b17032f">

`mvn test -Dsurefire.suiteXmlFiles=testng.xml`

<img width="1215" alt="Screenshot 2023-10-31 at 12 27 28 PM" src="https://github.com/PramodDutta/AdvanceSeleniumFrameworkTTA/assets/1409610/b0905741-d88d-4559-93c2-65433e668170">

---



---
