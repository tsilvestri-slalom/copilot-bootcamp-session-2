# Functional Requirements

## Overview

This document defines functional requirements for displaying and sorting todo items by age in the application.

## Functional Requirements

### FR-1: Display Todo Item Age

The system shall display the age of each todo item using days, hours, and minutes.

#### Acceptance Criteria

- Each todo item shall show an age value based on the time elapsed since the item was created.
- The displayed age shall include days, hours, and minutes.
- The age value shall update so that the displayed time remains accurate during use.
- If a todo item is less than one day old, the system shall still display the age using the same format.

### FR-2: Sort Todo Items by Age

The system shall allow the user to sort todo items by age in either ascending or descending order.

#### Acceptance Criteria

- The user shall be able to select an ascending age sort order.
- The user shall be able to select a descending age sort order.
- When ascending order is selected, todo items shall be ordered from newest to oldest.
- When descending order is selected, todo items shall be ordered from oldest to newest.
- Changing the sort order shall update the displayed todo list accordingly.