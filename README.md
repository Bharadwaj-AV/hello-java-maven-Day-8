![Screenshot 2025-04-20 185947](https://github.com/user-attachments/assets/0d303d19-5c0c-4d09-975f-f771d54c74dc)
![Screenshot 2025-04-20 192004](https://github.com/user-attachments/assets/170af341-f511-4d5f-b1c8-1efb32db2beb)

# Hello Java Maven

This is a simple **Java HelloWorld** project using **Maven** build tool.  
It prints a welcome message and is designed to demonstrate basic **CI/CD with Jenkins**.

---

## 📁 Project Structure

hello-java-maven/ ├── pom.xml └── src/ └── main/ └── java/ └── HelloWorld.java

## 📦 Build Tool

This project uses **Apache Maven** for compiling and packaging the code into a `.jar` file.

### 🔧 Maven Build Command

```bash
mvn clean package
This generates a target/hello-1.0.jar file.

🚀 Running the App
After building, run the application using:

java -cp target/hello-1.0.jar HelloWorld
Note: The .jar file is not executable because it doesn’t contain a Main-Class manifest entry. So we run it using the -cp option.

🛠️ Jenkins Integration
This project is used to demonstrate:

Jenkins installation on an EC2 instance (Ubuntu)

Jenkins Freestyle or Pipeline Job

Build automation using mvn clean package

Display "BUILD SUCCESS" in Jenkins console output

💡 Output
Hello, Jenkins + Maven!
