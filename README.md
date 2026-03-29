# The Family Menu - User Interface

## Purpose of the Application
The Family Menu is a meal planning web application designed for busy households. It allows users to browse meals, add selected meals to a meal plan, view recipe instructions, and access a consolidated grocery list generated from their selected meals. The application is intended to simplify weekly meal planning while also helping users estimate grocery costs by displaying the estimated cost per meal and cost per generated grocery list.

## Purpose of This Repository
This repository contains the user interface for The Family Menu. Its role in the overall application is to provide the frontend pages, layouts, styling, and user interactions that allow users to navigate the application and use its features.

The UI is responsible for presenting:
- the Home page
- the Meal Library
- the My Meal Plan page
- the My Grocery List page
- the login/create account flow
- recipe instruction overlays
- the stretch goal tag-based filter interface

This repository also stores the user-interface-related design documents used to guide development.

## Major UI Responsibilities
- Render responsive frontend pages using HTML, CSS, and Bootstrap
- Display meals in a clear, user-friendly interface
- Allow users to add meals to a plan
- Allow users to remove meals from a plan
- Allow users to view recipe instructions
- Display generated grocery list data returned by backend services
- Support tag-based meal filtering as a stretch feature

## Design Documents Included
See the `design` folder for the wireframes, storyboard, and style guide that guide this repository.

## Planned Technologies
- HTML
- CSS
- Bootstrap
- JavaScript

## Relationship to the Full Application
This repository handles the presentation layer only. It communicates with the backend service layer, which manages authentication, meal data, meal plans, grocery list generation, and database persistence.
