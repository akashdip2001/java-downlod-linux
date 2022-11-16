# How to install Java on Kali Linux
java downlod in linux from terminal

---

Install Java JDK on Kali
```
        $ sudo apt update
        $ sudo apt install default-jdk
        $ sudo apt-cache search openjdk // If you want to install a specific version of the JDK
        $ java --version                // Once the process is finished, you can verify the Java installation with the following command.
```
---
Write Java **Hello World** Program 
- your file name & Class name mast be same
```
public class HelloWorld {
   public static void main(String[] args) {
      System.out.println("Hello World");
   }
}
```
---
Compile Java Program
```
$ javac HelloWorld.java
```
---
To switch between Java versions, execute the following two commands while selecting the Java version you require.
```
$ sudo update-alternatives --config java
$ sudo update-alternatives --config javac
```
---
-Fedora https://docs.fedoraproject.org/en-US/quick-docs/installing-java/
-Redhat https://access.redhat.com/documentation/en-us/openjdk/8/html-single/installing_and_using_openjdk_8_for_rhel/index
-.deb file https://www.oracle.com/in/java/technologies/downloads/#jdk19-linux
