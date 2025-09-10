# Places-near-me Software – SRS Document

- Al-Azhar University – Gaza
- Faculty of Engineering & Information Technology
- Department of Software Engineering

- Prepared by: Sally Mohammed Abd-Alatti
- Supervised by: Eng. Heba Abu Skhail
- Semester: I 2022/2023

## 1. Project Overview
- Places-near-me is a mobile application designed to help users find facilities near their location.
- The app provides information about each facility, including contact details, services, ratings, and directions.
- Users can check in, rate, and give feedback for visited facilities.

## 2. Key Features
- Search for nearby facilities by category.
- View facilities on a map and as a list.
- Display nearest and most-rated facilities.
- Facility profiles with contact info and operating hours.
- Check-in, rate, and give feedback for visited facilities.
- Facility admin can manage profiles, view feedback, and set facility status.

## 3. Requirements
### 3.1 Functional
- User and admin account management.
- Facility search and category selection.
- Map display of facilities.
- Check-in, feedback, and rating system.

### 3.2 Non-Functional
- Android/iOS support.
- Fast map loading (within 3 seconds).
- Cross-platform compatibility.

## 4. Architecture
- Repository-based architecture with a central database for managing facility and user data.
- Advantages: supports data integrity, backup, and centralized management.
- Disadvantages: relies heavily on the central data repository.
