# Hello Java Maven

This is a simple **Java HelloWorld** project using **Maven** build tool.  
It prints a welcome message and is designed to demonstrate basic **CI/CD with Jenkins**.

---

## 📁 Project Structure

hello-java-maven/ ├── pom.xml └── src/ └── main/ └── java/ └── HelloWorld.java

yaml
Copy
Edit

---

## 📦 Build Tool

This project uses **Apache Maven** for compiling and packaging the code into a `.jar` file.

### 🔧 Maven Build Command

```bash
mvn clean package
This generates a target/hello-1.0.jar file.

🚀 Running the App
After building, run the application using:

bash
Copy
Edit
java -cp target/hello-1.0.jar HelloWorld
Note: The .jar file is not executable because it doesn’t contain a Main-Class manifest entry. So we run it using the -cp option.

🛠️ Jenkins Integration
This project is used to demonstrate:

Jenkins installation on an EC2 instance (Ubuntu)

Jenkins Freestyle or Pipeline Job

Build automation using mvn clean package

Display "BUILD SUCCESS" in Jenkins console output

💡 Output
bash
Copy
Edit
Hello, Jenkins + Maven!
