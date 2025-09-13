# Simple Notepad Application

A basic text editor application built with Java Swing that provides essential notepad functionality including creating, opening, and saving text files, along with basic text editing operations.

## Features

 - Create new text files
 - Open existing text files
 - Save text files
 - Cut, copy, and paste text operations
 - Simple about dialog with creator information
 - Intuitive GUI with menu bar

## Setup Instructions

### Prerequisites

 - Java Development Kit (JDK) 8 or later
 - Git (for cloning the repository)

### Installation and Running the Application

1. Clone the repository:
```bash
git clone <your-repository-url>
cd SimpleNotepad
```
2. Compile the Java source code:
```bash
javac SimpleNotepad.java
```
3. Run the application:
```bash
java SimpleNotepad
```
Alternatively, you can import the project into any Java IDE (Eclipse, IntelliJ IDEA, NetBeans) and run it from there.

## Usage

#### 1. File Operations:

 - New: Create a new document (Ctrl+N might not be implemented)
 - Open: Open an existing text file
 - Save: Save the current document
 - Exit: Close the application

#### Edit Operations:

 - Cut: Remove selected text and place it in clipboard
 - Copy: Copy selected text to clipboard
 - Paste: Insert clipboard content at cursor position

#### Help:

 - Display information about creator

## Assumptions and Notes

 - The application uses the system's default file encoding for reading and writing files
 - No database is required for this application as it works with local text files
 - The application follows a simple MVC architecture with the GUI built using Swing components
 - File operations use the standard JFileChooser dialog for file selection
 - Text area component automatically provides scrolling functionality for large documents

## Technical Details

 - Built with Java Swing for the graphical user interface
 - Uses standard Java I/O classes for file operations
 - Event handling implemented with ActionListener interfaces
 - Requires Java 8 or later to run

## My Information

 - Name: Pasindu Madhusha
 - Student ID: 2021s18785
 - Index No: s16199

