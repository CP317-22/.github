# <center> CP317A Project Requirements 2022 Fall<center>

##### <center>Lunshan (Shaun) Gao, Ph.D. P.Eng.<center>

##### <center>2022-08<center>

## Introduction

The project is a group of four students work. The purpose of this project is to provide an
opportunity for students experience what software engineering is, and to understand file input
and output from software perspective. The evaluation of the project consists of two portions
such that project presentation and project report. The presentation section measures your verbal
communication skills, and the report section measures your writing communication skills and the
understanding of software design document.

Project requirements

1. Design and develop a software application to read two text files and format the data
   output to a new file (Note: the format of input file and output file is described in
   Appendix B).

2. The software must use at least two of the following Object-Oriented programming
   features
   (1) Inheritance, (2) Polymorphism, (3) Encapsulation, (4) Abstraction

3. Re-engineering is permitted. However, you must understand the implementation in
   detail.

4. if your team selects re-engineering, you must tell the audiences about the source in the
   presentation and must cite the source in your project report. Otherwise, your team may
   get penalty.

5. Operating system, IDE, and computer language are your choice. However, if your project
   uses C++ and Windows OS, your team will have 5% bonus grade.

## Evaluation schemes

The project will be evaluated in two sections. One is project presentation, and the other is project
report. The evaluation rubrics are in appendixes of CP317A course syllabus that has been
uploaded in MyLearningSpace.

1. Project Presentation
   You will have 6 minutes to present your group project (3 minutes theory and 3 minutes
   demonstration). The presentation material such as PowerPoint slides must be delivered
   into myls.
2. Project Report
   Write a project report by end of this semester. The report should be like a software design
   document.

##### Notes

1.  **I suggest that you start with writing the software design document (SDD) in which you
    design how the software work. After you have a draft of the SDD, you start the
    implementation.**

2.  It is better to have regular meetings for the group work and to discuss the progresses
    and problems. For example, weekly meetings.

3.  It is better to divide the group project into partitions and certain individuals are
    responsible for certain parts. For example, two people focus on presentation and other

two focus on project report.

## Appendix A — reference resources

1. C++ APIs

    https://cplusplus.com/doc/tutorial/files/
    <br />

2. Java APIs

    https://www.javatpoint.com/java-io
    <br />

3. Python APIs

    https://docs.python.org/3/tutorial/inputoutput.html

## Appendix B

The formats of the two input files NameFile.txt and CourseFile.txt are as follows.

NameFile.txt

| Student ID (max length 9 byte) | Student Name (max length 20 byte) |
| ------------------------------ | --------------------------------- |
| 123456789                      | John Hay                          |
| 223456789                      | Mary Smith                        |
| ....                           | .....                             |

<br />

CourseFile.txt

| Student ID | Course Code | Test 1 (2 byte) | Test 2 (2 byte) | Test 3 (2 byte) | Final exam 92 byte) |
| ---------- | ----------- | --------------- | --------------- | --------------- | ------------------- |
| 423456789  | CP317       | 75              | 80              | 60              | 70                  |
| 223456789  | CP414       | 80              | 90              | 50              | 75                  |
| 123456789  | CP460       | 60              | 70              | 80              | 80                  |
| ....       | .....       |                 |                 |                 |                     |

**Note 1**: the student Id, student name, course code, and the grades will be separated with comma in the input files. The two input files will be uploaded in myls around week 7.

**Note 2**: the student ID and students’ name are unique. However, one student may take multiple courses.

The format of the output file is as follows.

| Student ID (9 byte) | Student Name (20 byte) | Course Code (6 byte) | Final Grade (test 1, 2, 33x20%, final exam 40%) |
| ------------------- | ---------------------- | -------------------- | ----------------------------------------------- |
| 123456789           | John Hay               | CP460                | 74                                              |
| 223456789           | Mary Smith             | CP414                | 74                                              |
| ....                | .....                  |                      |                                                 |

**Note 3**: each test weighs 20% and the final exam weighs 40%. The final grade is calculated with the following: (test,1,2,3) 3x20% + (final exam) 40% = 100%.
