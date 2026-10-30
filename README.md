# Maternal Health Appointment Reminder System

**PROG101 Principles of Programming Logic and Design | Individual Assignment 1**


## Overview
This repository holds the logical design of a system, not working software. It explains how a community clinic in Sierra Leone could keep track of antenatal care visits, note which women attended, and respond when a visit is missed. The project contributes to **SDG 3: Good Health and Well-being**.

## The problem
Many pregnant women miss their antenatal appointments, and clinics often have no simple, organised way to notice or remind them. A missed visit can pass unseen until a complication arises.

## How the system works
1. The health worker types in the patient's name, phone number and current week of pregnancy.
2. The system plans a visit every 4 weeks, up to week 36.
3. At each visit, the health worker enters 1 if she attended or 0 if she did not.
4. An attended visit is confirmed. A missed visit produces a simulated SMS reminder.
5. At the end, a summary reports visits attended, visits missed and a risk level of LOW, MEDIUM or HIGH.

## Repository contents
| File | Description |
|---|---|
| `Maternal_Health_Reminder.fprg` | Flowgorithm file with the Main flowchart and 4 function flowcharts |
| `PROG101_Assignment1__.pdf` | Complete written report |
| `pseudocode.txt` | Pseudocode for the whole system |
| `flowcharts/` | Exported PNG images of the flowcharts |
| `LICENSE` | MIT License |

## Programming concepts demonstrated
Variables, constants, decision structures (IF/ELSE), repetition (WHILE), Boolean logic, functions and modular design.

## Opening the flowchart
1. Download the free Flowgorithm program from flowgorithm.org.
2. Open the file `Maternal_Health_Reminder.fprg`.
3. Press **F5** to run the flowchart.

## Author
Student_name: Aina B.C.E Davies
Student_ID: 905006600



## License
This project is shared under the MIT License. Anyone may use, copy, change and distribute it, provided the license notice stays with it. The full text is in the `LICENSE` file.
