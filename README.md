# exam-timetable1
the exam timetable project 
# Exam Timetable Scheduling Using Graph Colouring

## Project Information

- **Project Title:** Exam Timetable Scheduling Using Graph Colouring
- **Student Name:** Syed Moahmmed
- **USN:** 1CR25CS414
- **Department:** Computer Science and Engineering
- **Semester and Section:** 5C
- **College:** CMRIT
- **Project Guide:** bibi maam

## 1. Project Overview

Exam Timetable Scheduling is a graph-colouring problem that aims to generate an efficient examination timetable while avoiding clashes between courses.

Each course is represented as a vertex in a graph. An edge connects two courses when they have at least one common student. Different colours represent different examination time slots.

The objective is to assign time slots to all courses so that no two conflicting courses are scheduled at the same time.

## 2. Problem Statement

A university offers N courses. Some courses conflict because students are enrolled in both courses. The system must schedule examinations while ensuring that conflicting courses are assigned different time slots.

The challenge is to generate a valid timetable using graph-colouring techniques while minimizing the number of time slots where possible.

## 3. Objectives

- Represent courses and examination conflicts using a graph.
- Apply graph-colouring algorithms to assign examination slots.
- Prevent students from having overlapping examinations.
- Generate a valid and easy-to-understand examination timetable.
- Minimize the number of examination time slots where possible.
- Handle special cases such as isolated courses and highly conflicting courses.

## 4. Proposed Methodology

1. Collect the list of courses.
2. Identify conflicts between courses.
3. Construct an undirected conflict graph.
4. Apply a graph-colouring algorithm, such as Greedy Colouring or DSATUR.
5. Assign a time slot to each course based on its colour.
6. Validate the timetable to ensure that no conflicting courses share a slot.
7. Display the final timetable and the number of time slots used.

## 5. Technologies Used

- **Programming Language:** Python
- **Core Concept:** Graph Theory and Graph Colouring
- **Algorithms:** Greedy Graph Colouring / DSATUR
- **Data Structures:** Graphs, adjacency lists, dictionaries, and sets

## 6. Expected Output

The system should produce a timetable that assigns each course to an examination time slot without any conflicts.

It should also report the total number of time slots used and confirm whether all conflict constraints have been satisfied.

## 7. Applications

- University examination scheduling
- College internal examination planning
- Academic resource planning
- General scheduling problems involving conflicting activities


Computer Science and Engineering
