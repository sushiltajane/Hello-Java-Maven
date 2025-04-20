# Hello-Java-Maven
# Java Maven Hello World with Jenkins

This project demonstrates a simple Java "Hello World" app built using **Maven** and automated via a **Jenkins Freestyle Job**.

## 📦 Project Structure

hello-java-maven/ ├── pom.xml └── src/ └── main/ └── java/ └── HelloWorld.java


## 🧰 Requirements
- Java JDK 8 or 11  
- Maven  
- Jenkins (installed locally or via Docker)

## 🚀 Setup Steps
1. Clone this repo or create the above structure.
2. Run Jenkins (if using Docker):

docker run -p 8080:8080 jenkins/jenkins:lts

3. Configure Maven in Jenkins (Global Tool Configuration).
4. Create a Freestyle Project and add build step: `Invoke top-level Maven targets` with goal `clean package`.
5. Build the project and check the console output for `BUILD SUCCESS`.

## ✅ Output
Console will display:
Hello, Jenkins + Maven! BUILD SUCCESS

# Java Maven Hello World with Jenkins
![maven](https://github.com/user-attachments/assets/aba5eadf-b4a3-4a34-a426-1020af77652f)





