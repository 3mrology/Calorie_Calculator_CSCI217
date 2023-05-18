Person Data Report Generator

This Java program collects information about individuals, calculates their Body Mass Index (BMI) and Basal Metabolic Rate (BMR), and generates a comprehensive report in both text and binary formats. The report includes individual data, the person with the highest BMI, and the average BMR for optimal males and females.
Usage

    Clone the repository and navigate to the project directory.
    Compile the Java source files using the following command:

css

javac Main.java Person.java

    Run the compiled program:

css

java Main

    The program prompts you to enter the number of people for the report.
    Provide the required information for each person:
        Name
        Age
        Weight
        Height
        Gender (m or f)
    After entering the information for all people, the program generates a report.
    The generated report is saved in two formats:
        Text format: A file named report.txt contains the report in human-readable form.
        Binary format: A file named report.bin stores the report in binary format.

Program Workflow

The program consists of two classes:

    Main: This class contains the main method and handles the user interface, data input, and report generation.
    Person: This class represents an individual and contains methods to calculate BMI, BMR, and set various attributes. It also calculates the average BMR for optimal males and females.

The program flow can be summarized as follows:

    User is prompted to enter the number of people for the report.
    Information about each person is collected, including their name, age, weight, height, and gender.
    The program calculates the BMI and BMR for each person.
    The person with the highest BMI is identified.
    The collected data is written to both a text file (report.txt) and a binary file (report.bin).
    The program generates a report displaying the collected data, the person with the highest BMI, and the average BMR for optimal males and females.

Sample Report

People data:

    Person 1:
        Name: John
        Age: 30
        Weight: 75.5 kg
        Height: 180.0 cm
        Gender: Male
        BMI: 23.30
        BMR: 1779.0
        Status: Optimal
    Person 2:
        Name: Lisa
        Age: 25
        Weight: 62.0 kg
        Height: 165.0 cm
        Gender: Female
        BMI: 22.81
        BMR: 1354.7
        Status: Optimal
        ...
        Highest BMI:
    Name: David
    Age: 28
    Weight: 80.2 kg
    Height: 175.0 cm
    Gender: Male
    BMI: 26.16
    BMR: 1864.9
    Status: Overweight

Average BMR:

    Average BMR for optimal males: 1687.6
    Average BMR for optimal females: 1425.8
