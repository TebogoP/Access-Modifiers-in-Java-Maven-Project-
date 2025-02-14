# Access Modifiers in Java (Maven Project) 🏡🌆

# 📌 Overview

This project demonstrates Java Access Modifiers (public, private, protected, and default) using the house and city analogy. It is built using Maven and follows a structured project layout.

## 📂 Project Structure
```
access-modifiers-demo/
│── pom.xml                   # Maven configuration file
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           ├── Main.java                  # Main execution class
│   │   │           ├── accessmodifiers/
│   │   │           │   ├── CityPark.java          # Public class
│   │   │           │   ├── GatedCommunity.java    # Default access class
│   │   │           │   ├── House.java             # Protected members
│   │   │           │   ├── PrivateHouse.java      # Private members
│   │   │           │   ├── RelativeHouse.java     # Subclass accessing protected members
│   ├── test/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           ├── AccessModifiersTest.java   # Unit tests
│── target/                   # Compiled output
│── .gitignore                 # Git ignore file
│── README.md                  # Project documentation
```
## 🚀 Getting Started

1️⃣ Prerequisites

  - Java 8+ installed

  - Maven 3+ installed

2️⃣ Clone the Repository
```
git clone https://github.com/your-repo/access-modifiers-demo.git
cd access-modifiers-demo
```
3️⃣ Build the Project
```
mvn clean install
```
4️⃣ Run the Application
```
mvn exec:java -Dexec.mainClass="com.example.Main"
```
🎯 Expected Output
```
Anyone in the city can visit the public park!
Visiting: Relaxing in the backyard.
Inside the house...
This is a private secret room.
```
🏗️ Access Modifier Explanation

Modifier

Behavior

Example

public

Accessible anywhere

CityPark

private

Accessible only within the class

PrivateHouse

protected

Accessible within the same package & subclasses

House, RelativeHouse

default

Accessible only within the same package

GatedCommunity

🛠️ Running Tests
```
mvn test
```
This runs unit tests defined in AccessModifiersTest.java.

📌 Future Enhancements

Add more package-private examples

Extend test coverage

Implement real-world applications of access modifiers

📜 License

This project is licensed under the MIT License.
