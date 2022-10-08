# Dmoney-Load-Test-Using-JMeter
## Tecnhnology And Tool Used
- JMeter
- Java JDK
- Google Sheet

# Scenario
 - Load Testing

## How To Run This Project

1. Download the .jmx file
2. Open CMD or your CLI mode Type the following commands:

```jmeter -n -t [path of the dot jmx file] -l [path of thr reports.csv file] -e -o [blank folder html path to generate html report]```

3. here ```-n``` instruct jmeter run the test in non-GUI mode ```-t``` specify the path of .jmx file. ```-l``` instruct to write into log file results ```-e -o``` location of the output folder
## Load test from CLI (Command Line Interface)
- ```jmeter -n -t yourFile.jmx -l yourFile.csv```
## Generate Report
 - ```jmeter -n -t yourFile.jmx -l yourFile.csv -e -o Reports```
## Prerequisite
Install JDK 8 or 11
- To check from cmd, hit:
```java –version```

## Performance Test Report
![image](https://user-images.githubusercontent.com/114859893/194729550-d236da4b-6cc2-43e2-b40e-12eefb4cd49c.png)
![image](https://user-images.githubusercontent.com/114859893/194729567-13672c9b-0068-4204-beac-a6192812e4d8.png)
