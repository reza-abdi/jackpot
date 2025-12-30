# 🎰 Jackpot

## CMPUT 301 – Software Engineering (Event Lottery Android Application)

Jackpot is a Java-based Android application developed as part of CMPUT 301: Software Engineering at the University of Alberta.
The project demonstrates the design and implementation of a complete, interactive mobile application using object-oriented principles, cloud-backed persistence, external APIs, and agile team practices.

This repository reflects the final checkpoint (Project Part 4) state of the project, with consistent updates and refinements from earlier milestones.


### 📘 Course & Project Context

+ Course: CMPUT 301 – Software Engineering
+ Institution: University of Alberta
+ Platform: Android
+ Primary Language: Java
+ Backend Requirement: Firebase (Firestore)
+ Process: Agile / Scrum-style development
+ Artifacts: UML diagrams, tests, demos, documented code
  
The project satisfies all mandatory requirements across Assignment 1 and Project Parts 0–4, including UML documentation, testing, demos, and collaborative GitHub usage.

### 📱 Application Overview
Jackpot is an interactive Android application designed to provide users with data-driven functionality supported by cloud services.<br>
The application integrates authentication, persistent storage, mapping, media handling, and device capabilities into a cohesive mobile experience.

The system was designed with:
+ Clear separation of concerns
+ Lifecycle-aware components
+ Maintainable and extensible object-oriented architecture

### ✨ Implemented Features

#### 🔐 User Authentication
+ Firebase Authentication
#### 🗄️ Cloud Data Management
+ Firebase Firestore
+ Firebase Realtime Database
#### ☁️ Media Storage
+  Firebase Storage for user-uploaded content
#### 🗺️ Map Integration
+ OSMDroid for map rendering and interaction
#### 📍 Location & Nearby Services
+ Google Play Services Nearby
#### 🏪 Places Integration
+ Google Places API
#### 📷 Efficient Image Loading
+ Glide for asynchronous loading and caching
#### 📸 QR Scanning
+ ZXing Embedded
#### 🧭 Navigation
+ Fragment-based navigation using Android Navigation Component
#### 🎨 User Interface
+ Material Design components
+ Responsive layouts using ConstraintLayout and RecyclerView
#### 🧪 Testing
+ Unit tests (JUnit)
+ Instrumentation/UI tests (Espresso)

### 🛠️ Technology Stack

#### Programming Languages
+ Java – all application logic
+ XML – layouts and resources
+ Kotlin (Gradle Kotlin DSL) – build configuration only

#### Android & Jetpack Libraries
+ AndroidX AppCompat
+ Material Components
+ RecyclerView
+ ConstraintLayout
+ Lifecycle (ViewModel, LiveData)
+ Navigation Component

#### Google & Firebase Services
+ Firebase Authentication
+ Firebase Firestore
+ Firebase Realtime Database
+ Firebase Storage
+ Firebase BoM
+ Google Places API
+ Google Play Services Nearby

#### Third-Party Libraries
+ OSMDroid – map rendering
+ Glide – image loading and caching
+ ZXing Embedded – QR / barcode scanning

#### Tooling
+ Android Studio
+ Gradle & Gradle Wrapper
+ GitHub (version control and collaboration)

### 📂 Repository Structure
```
Jackpot/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/jackpot/   # Java source code
│   │   │   ├── res/                        # XML layouts & resources
│   │   │   └── AndroidManifest.xml
│   │   ├── test/                           # Unit tests
│   │   └── androidTest/                    # Instrumentation tests
│   └── build.gradle.kts
├── gradle/
├── gradlew
├── settings.gradle.kts
└── README.md
```

### 🧱 Architecture & Design
+ Object-oriented design documented using UML class diagrams
+ Separation between:
  + UI (Activities / Fragments)
  + Control logic (ViewModels)
  + Data models and Firebase access
+ Lifecycle-aware components using ViewModel and LiveData
+ Design evolved incrementally across project milestones

All source files include descriptive comments, and model classes provide Javadoc documentation, as required by CMPUT 301.

### 🧪 Testing Strategy
+ Unit Tests
  + JUnit tests for model and control logic
+ Instrumentation Tests
  + Espresso and AndroidX Test for UI and intent-based testing

Tests are included in the repository and reflect realistic usage scenarios, in line with project requirements.

### ⚙️ Build & Setup Instructions
TODO

### 🔐 Permissions Used
+ Internet access
+ Location services
+ Camera (QR / barcode scanning)
+ Storage access (media uploads)

### 🤝 Team Collaboration & Process
+ Developed as a team-based project
+ Regular and consistent GitHub commits by all members
+ Weekly sprint planning and reviews conducted in labs
+ TA feedback addressed at each milestone
+ Peer evaluations completed for individual contribution assessment





