Hospital Resource Allocator — Python

A Python-based simulation project designed to demonstrate how limited hospital resources can be allocated to patients with different urgency levels and arrival times.

Project Overview

The system simulates a 120-minute hospital environment with 60 patient records and limited resources:

* 5 Doctors
* 4 Rooms
* 3 Equipment units

Patients are scheduled based on their urgency level and arrival time while the system tracks resource availability, waiting times, resource utilization, and untreated patients.

Key Features

* Greedy scheduling approach for prioritizing patients
* Optimized Bubble Sort for ordering patients by arrival time and urgency
* Dynamic allocation of Doctors, Rooms, and Equipment
* Individual and average patient waiting time calculation
* Resource utilization calculation
* Identification of patients who could not be treated within the simulation time
* Interactive Tkinter GUI for displaying the treatment schedule and performance metrics
* Urgency-based visualization of scheduled patients

Algorithms & Data Structures

* Greedy Scheduling
* Optimized Bubble Sort
* Lists
* Dictionaries
* Resource Availability Tracking
* Scheduling Simulation

Results

The system generates a treatment schedule containing patient IDs, treatment types, start times, end times, and urgency levels.

It also displays average waiting times, resource utilization percentages, and untreated patients through the graphical interface.

Technologies & Concepts

* Python
* Tkinter
* Data Structures
* Algorithms
* Greedy Scheduling
* Bubble Sort
* Simulation
* Resource Scheduling

How to Run

Run HospitalResourceAllocator.py using Python.

The application will open a graphical interface where you can run the hospital scheduling simulation and view the generated results.
