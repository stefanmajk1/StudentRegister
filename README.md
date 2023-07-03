# StudentRegister

StudentRegister is an Android application that allows users to register and manage student information. It utilizes the Room Persistence Library for data storage and retrieval and implements a RecyclerView to display a list of registered students. Users can add new students, update existing student information, and delete students from the list.

## Features

- Register new students with name and email information
- Update and delete existing student records
- Display a list of registered students using RecyclerView

## Installation

1. Clone this repository to your computer.
2. Open the project in the Android Studio development environment.
3. Connect an Android device or launch an emulator.
4. Run the project by clicking the "Run" button.

## Dependencies

The "StudentRegister" application implements the following dependencies:

- AndroidX AppCompat Library
- AndroidX Lifecycle Library
- Room Persistence Library

To include these dependencies in your own project, you can add the following lines to your app-level build.gradle file:

## gradle
dependencies {
    implementation 'androidx.appcompat:appcompat:1.3.1'
    implementation 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.3.1'
    implementation 'androidx.room:room-runtime:2.3.0'
    annotationProcessor 'androidx.room:room-compiler:2.3.0'
}

## Usage
- Launch the application on your Android device or emulator.
- To register a new student, enter their name and email in the provided fields.
- Click the "Save" button to add the student to the list.
- To update an existing student's information, click on the student's name in the list.
- Update the name and email fields and click the "Update" button to save the changes.
- To delete a student from the list, click on the student's name in the list.
- Click the "Delete" button to remove the student from the list.
## Technical Information
The application is developed in the Android Studio development environment and utilizes the following technologies and components:

- Kotlin programming language
- Room Persistence Library for data storage and retrieval
- RecyclerView for displaying a list of students
- ViewModel and LiveData for managing data and UI updates
