Intelligent Exam Scheduling System
Overview
The Intelligent Exam Scheduling System is a Python-based application designed to automate and optimize the scheduling of exams. Utilizing genetic algorithms, this system aims to generate efficient and conflict-free timetables. The project includes a user-friendly interface built with Tkinter for easy management of courses, instructors, and student registrations.

Features
Genetic Algorithm: Utilizes genetic algorithms to find optimal scheduling solutions.
User Interface: Built with Tkinter for a seamless and intuitive user experience.
Course and Registration Management: Easily manage courses, instructors, and student registrations.
Conflict Resolution: Handles scheduling conflicts intelligently to minimize issues.
Customizable Parameters: Adjustable population size, crossover probability, and mutation probability for the genetic algorithm.
Getting Started
Prerequisites
Python 3.x
Tkinter (usually comes pre-installed with Python)
Numpy
Collections
CSV
Installation
Clone the repository:
sh

Navigate to the project directory:
sh

cd intelligent-exam-scheduling-system
Install the required dependencies:
sh

pip install numpy
Usage
Run the main application:
sh

python main.py
Use the Tkinter interface to:
Add and manage courses and instructors.
Register students for courses.
Configure and run the scheduling algorithm.
File Structure
main.py: The main script to run the application.
README.md: Project documentation.
Other supporting scripts and data files.
Project Details
Classes
Course: Stores course details including course code, name, and number.
Registration: Manages student registrations for courses.
Genetic Algorithm Parameters
Population Size: Default is 100.
Crossover Probability: Default is 0.7.
Mutation Probability: Default is 0.1.
