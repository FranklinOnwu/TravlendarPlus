
# TRAVLENDAR+

This repository contains the full documentation for a meeting scheduler application, which should be implemented in Java. The project is part of the Software Engineering 2 course of Politecnico di Milano, a.y. 2017-2018.

## Getting started

Travlendar+ provides a flexible and fully-featured calendar support that considers the travel time between meetings. The application supports a multitude of travel means, including walking, biking, public transportation, and driving. It is designed to be compatible with the public transportation in Milan only.

## Requirements Analysis and Specification Document

This document introduces the application goals. It is composed as follows:
- Introduction
  * Purpose
  * Scope
  * Definitions, acronyms, abbreviations
    + Definitions
    + Acronyms
    + Abbreviations
  * Revision history
  * Reference documents
  * Document structure
- Overall description
  * Product perspective
  * Product functions
  * User characteristics
  * Assumptions
    + Application assumptions
    + Domain assumptions
    + Text assumptions
- Specific requirements
  * External interface requirements
    + User interfaces
    + Hardware interfaces
    + Software interfaces
    + Communication interfaces
  * Functional requirements
    + Functional requirements list
    + Use case diagrams
    + Use case tables
    + Class diagram
    + Sequence diagrams
  * Design constraints
    + Hardware limitations
  * Software system attributes
    + Reliability
    + Availability
    + Security
    + Maintainability
  * Scenarios
    + Scenario 1
    + Scenario 2
    + Scenario 3
    + Scenario 4
    + Scenario 5
    + Scenario 6
  * Formal analysis using alloy
    + Source code
    + Output
    + Generated world
  * Effort spent

## Design Document

This document introduces the application design. It is composed as follows:
- Introduction
  * Purpose
  * Scope
  * Definitions, acronyms, abbreviations
    + Definitions
    + Acronyms
    + Abbreviations
  * Revision history
  * Reference documents
  * Document structure
- Architectural design
  * Overview
  * Component view
    + Device
    + Application server
    + Database server
    + External services
  * Deployment view
    + Device
    + Application server
    + Database server
  * Runtime view
    + Creation of a standard event or a flexible event
    + Creation of a lasting event
    + Creation of a transfer event
    + Start a travel and purchase a ticket
  * Component interfaces
  * Selected architectural styles and patterns
    + Architectural styles
    + Patterns
- Algorithm design
  * Cheapest travel algorithm
  * Most ecological travel algorithm
  * Quickest travel algorithm
  * Dispatcher algorithm
- User interface design
  * User interface
  * User interface diagram
- Requirements traceability
- Implementation, integration and test plan
  * Preconditions
  * Proposed plan
    + White-box testing
    + Local Model-View-Control pattern testing
    + Dispatcher pattern testing
    + Model and Data testing
    + EventController testing
    + Model-View-Control pattern testing
- Effort spent

## Original work

This project is based on the original [Travlendar](http://score-contest.org/2018/projects/travlendar.php) topic, proposed during the SCORE 2018 Contest.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
