```markdown
# 🛠️ Jenkins CI/CD Test Project – Python & Java

This project demonstrates automated unit testing and continuous integration using **Jenkins**, with test cases written in both **Java (JUnit)** and **Python (unittest)**. It simulates a basic CI/CD pipeline for validating multi-language codebases.

---

## 📁 Project Structure

```

JenkinsProjects-main/
├── JenkinsFile                 # Jenkins pipeline definition
├── requirements.txt            # Python dependencies
├── java\_math/                  # Java code & Maven config
│   ├── pom.xml
│   └── src/
│       ├── main/java/MathUtils.java
│       └── test/java/MathUtilsTest.java
├── python\_math/                # Python code & tests
│   ├── math\_utils.py
│   ├── test\_math\_utils.py
│   └── gfg.xml (test results)

````

---

## 🔧 Technologies & Tools

- **Languages**: Java, Python
- **Testing Frameworks**:
  - JUnit for Java
  - unittest for Python
- **CI/CD**: Jenkins (with `JenkinsFile`)
- **Build Tool**: Maven
- **Version Control**: Git & GitHub

---

## ⚙️ How to Run Tests

### 🔹 Python

```bash
pip install -r requirements.txt
python -m unittest python_math/test_math_utils.py
````

### 🔹 Java (using Maven)

```bash
cd java_math
mvn test
```

---

## 🚀 Jenkins CI/CD

This project uses Jenkins to:

* Pull code from GitHub
* Install dependencies
* Run Java & Python unit tests
* Report build and test status

Jenkins pipeline defined in `JenkinsFile`.

---

## ✅ Use Cases

* CI/CD demo project for DevOps and QA job applications
* Example of language-agnostic test automation
* Practice for Jenkins pipelines and multi-language projects

---

## 👨‍💻 Author

**Akshay Kumar Reddy Yannam**
Graduate Student, MS in Computer Science @ CSUDH
📎 [LinkedIn](https://linkedin.com/in/akshay-kumarreddy-93552236a)
🐙 [GitHub](https://github.com/Akshaykumarreddy630)

---
