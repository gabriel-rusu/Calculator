<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://raw.githubusercontent.com/RusuGabriel/Calculator/master/src/main/resources/Calculator.png" alt="Project logo"></a>
</p>

<h1 align="center">Calculator</h3>


<p align="center"> A simple Java Calculator made for fun that can calculate expressions using my version of Shunting-yard 
 algorithm.
    <br> 
</p>

## 📝 Table of Contents
- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Built Using](#built_using)
- [TODO](/TODO.md)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>
This project is an implementation of the popular Calculator app with a GUI that resembles the iPhone design and colours and currently supports basic operations and nested expression calculus that contains the following operations:
- addition
- difference
- multiplication
- division

## 🏁 Getting Started <a name = "getting_started"></a>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
To check if you already have the requirements
run the following command(cmd/linux terminal):
- for __Java__: ``` java --version```
- for __Maven__: ``` mvn --version ```

If you don't have the requirements above mentioned you should follow the following links to install them:
- [Maven](https://maven.apache.org/)
- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk14-downloads.html)

### Installing
To run the app you should follow the next steps, after installing the requirements. In the root folder of the project type:

```
mvn install
```

If the above command succeeds you should have a new folder called target. After this to run the app you should type:
```
mvn exec:java
```

## 🔧 Running the tests <a name = "tests"></a>
To run the unit-tests on your local computer type the following command: ```mvn test```

## 🎈 Usage <a name="usage"></a>
After running the ```mvn exec:java``` command you should be ready to use the Calculator app developed in this project.

## ⛏️ Built Using <a name = "built_using"></a>
- [Maven](https://maven.apache.org/) - build tool
- [Java 14 JDK](https://www.oracle.com/java/technologies/javase-jdk14-downloads.html) - virtual machine needed to run & compile the Java code
- [Visual Studio Code](https://code.visualstudio.com/) - code editor


## ✍️ Authors <a name = "authors"></a>
- [@gabriel-rusu](https://github.com/gabriel-rusu) - Idea & Initial work
