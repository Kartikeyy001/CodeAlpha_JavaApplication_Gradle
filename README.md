# ☕ CodeAlpha Java Application using Gradle

A Java application developed using Gradle to demonstrate build automation, dependency management, and project execution. This project was completed as part of the CodeAlpha DevOps Internship and showcases the use of Gradle for simplifying Java development workflows.

---

## 📌 Project Objective

The objective of this project is to:

- Automate Java application builds using Gradle
- Manage project dependencies efficiently
- Execute Java applications through Gradle
- Understand build automation concepts
- Learn DevOps practices in Java development

---

## 🛠️ Technologies Used

- Java
- Gradle
- Git
- GitHub

---

## 📂 Project Structure

```text
CodeAlpha_JavaApplication_Gradle
│
├── screenshots
│   ├── build_success.png
│   └── output.png
│
├── src
│   └── main
│       └── java
│           └── App.java
│
├── README.md
├── build.gradle
└── settings.gradle
```

---

## 📄 Source Code

### App.java

```java
public class App {
    public static void main(String[] args) {
        System.out.println("Hello from CodeAlpha Gradle Project!");
    }
}
```

---

## ⚙️ Build Configuration

### build.gradle

```gradle
plugins {
    id 'java'
    id 'application'
}

repositories {
    mavenCentral()
}

application {
    mainClass = 'App'
}
```

---

## 🚀 How to Run

### Build the Project

```bash
gradle build
```

### Run the Application

```bash
gradle run
```

---

## ✅ Output

```text
Hello from CodeAlpha Gradle Project!
```

---

## 📸 Screenshots

### Build Successful

![Build Success](screenshots/build_success.png)

### Application Output

![Output](screenshots/output.png)

---

## 🎯 Learning Outcomes

- Java project structure
- Gradle build automation
- Dependency management
- Project execution using Gradle
- Basic DevOps workflow understanding
- Source code management with GitHub

---

## 👨‍💻 Author

**Kartik Gupta**

DevOps Intern – CodeAlpha

---

## 📜 Internship Task

This project was developed as part of the **CodeAlpha DevOps Internship Program** under **Task 3: Java Application using Gradle**.
