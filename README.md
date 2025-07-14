# Bachelor Thesis: Developing a Concept for Automated Testing of IPC Middleware – Demonstrated with eCAL

## Get the PDF - Version
Latest Version of the Bachelor Thesis:
-->📥 Download [Bachelor_thesis.pdf](https://github.com/EmirTutar/bachelor-thesis-ipc-testing/releases/latest/download/Bachelor_thesis.pdf)

## Author
**Emircan Tutar**  
 
Ravensburg-Weingarten University of Applied Sciences

Study Program: Applied Computer Science 

## Related Projects

- [eCAL (Main Repository)](https://github.com/eclipse-ecal/ecal)  
  Official repository of the eCAL communication middleware by the Eclipse Foundation.

- [eCAL Test Suite (Official)](https://github.com/eclipse-ecal/ecal-test-suite)  
  Official test suite for eCAL, developed as part of this Bachelor's thesis. It implements the automated testing approach introduced and evaluated in the thesis.

- [Initial Prototype: eCAL Test Framework](https://github.com/EmirTutar/ECAL_Test_Framework)  
  Early development version of the test suite, later replaced by the official ecal test suite repository.

## Overview
This bachelor's thesis deals with developing and evaluating a system testing framework for Inter-Process Communication (IPC) based on eCAL (enhanced Communication Abstraction Layer). The aim is to create a standardized and reliable method to test distributed applications, ensuring stable communication, robustness, and performance in realistic scenarios.

## Motivation
As distributed systems become increasingly complex and requirements grow in industries such as automotive, robotics, and IoT, reliable middleware solutions become more important. eCAL is a IPC Middleware, but currently, there is no standardized method for Automated Integration testing.

This thesis addresses this gap by:
- Creating a systematic approach to integration tests
- Developing specific test cases and automation
- Evaluating test results and integrating them into CI/CD pipelines

## Main Topics
- Basics of IPC and eCAL architecture
- Defining requirements and test cases
- Development and implementation of tests
- Evaluation of test results
- Automation and integration into CI/CD

## Repository Structure
```
BA_Ecal_Test_Framework
 ├── Documentation
 │   ├── Doku.tex (LaTeX file of the thesis)
 │   ├── Doku.pdf (Localy builded PDF and pushed)
 │   └── Images
 │       └── (.png files)
 │   └── Expose
 │       └── Expose.pdf (An overview of the Thesis)
 │   └── Chapters
 │       └── (.tex files)
 ├── Source
 │   └── (Code files)
 └── README.md
```

## Automated Builds
The bachelor thesis (PDF) is automatically compiled after each push using GitHub Actions.  
You can download the latest compiled PDF from **[GitHub Actions → Artifacts](https://github.com/EmirTutar/bachelor-thesis-ipc-testing/actions?query=workflow%3A"Build+PDF")**.  
📌 **Note:** The downloaded file is a `.zip` archive. Extract it to access the `Bachelor_thesis.pdf`.
