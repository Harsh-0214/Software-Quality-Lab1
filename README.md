# Software-Quality LAB 1 -- Project Deliverable 1 -- Maven &amp; Unit Testing
*By: Harsh Tamakuwala 100824220*
## Repository Link: [SOFE3980U-Lab1](https://github.com/GeorgeDaoud3/SOFE3980U-Lab1.git)

## Video Link: [Lab 1 Video](https://drive.google.com/file/d/1yhtsjZkByK-beD6H7ReY9c_uSyZhXzvj/view?usp=drive_link)

## Lab Report Link: [Lab 1 Report](https://docs.google.com/document/d/1fmWB7UkoesYc5b5mPXv3vNzrAomtXwaIhxbxws1enOM/edit?usp=sharing)

# Running Instructions

To run the code in Windows PowerShell, follow these steps:

1. **Navigate to the Project Directory:**
   - Open Windows PowerShell.
   - Use the `cd` command to navigate to the "BinaryCalculator" folder:
     ```
     cd path_to_BinaryCalculator_folder
     ```
   Replace `path_to_BinaryCalculator_folder` with the actual path to your "BinaryCalculator" folder.

2. **Build the Project:**
   - Run the following command to clean the project, generate documentation, and create a JAR file with dependencies:
     ```
     mvn clean site assembly:single
     ```

3. **Run the JAR File:**
   - Once the build process is complete, execute the following command to run the JAR file:
     ```
     java -jar target\BinaryCalculator-1.0.0-jar-with-dependencies.jar
     ```

By following these steps, you will be able to build and run the project successfully in Windows PowerShell and the Target file will contain the Test Documentation of the application.


## Additional Resources:
- [Apache Maven Official Website](https://maven.apache.org/)
- [Maven Documentation](https://maven.apache.org/guides/index.html)
