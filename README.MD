# Code Group Generator

This repository contains a web-based tool for generating random groups from a list of students. The project was developed as part of the Progetto Code initiative.

## Repository Structure

The repository is organized as follows:

- **src/**: Source code directory
  - **css/**: Styling files
    - **font/**: Custom fonts
    - **styles.css**: Main stylesheet
  - **js/**: JavaScript files
    - **scripts.js**: Main application logic
  - **index.html**: Main HTML file

## Features

The Code Group Generator offers the following features:

- **Student Management**
  - Add students to a list
  - Reset the student list
  - Export student list to a file
  - Import student list from a file

- **Group Generation**
  - Create random groups of students
  - Customize group size (2-7 students per group)
  - View generated groups

## How to Use

1. **Adding Students**:
   - Enter a student name in the input field
   - Click "Aggiungi" to add the student to the list
   - The student will appear in the "Lista Studenti" section

2. **Managing Student List**:
   - Click "Reset Lista" to clear all students
   - Use "Esporta Lista Studenti" to save the current list
   - Use "Importa Lista Studenti" to load a previously saved list

3. **Generating Groups**:
   - Select the desired group size from the dropdown menu
   - Click "Genera" to create random groups
   - The groups will be displayed in the "Genera Gruppi" section

## Technical Implementation

The application is built using:
- HTML for structure
- CSS for styling
- JavaScript for functionality

No external libraries or frameworks are required except for Font Awesome, which is loaded via CDN for the user icons.

## Requirements

- A modern web browser
- No server-side components required (runs entirely in the browser)

## Getting Started

To use the Code Group Generator:

1. Clone this repository
2. Open `src/index.html` in your web browser
3. Start adding students and generating groups

Alternatively, you can access the tool by hosting the files on any web server.

---

*This repository was created as part of the educational journey at Progetto Code.*

        