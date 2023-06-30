# JuniorSchool
JuniorSchool is a collection of Github repositories, all related to one another and all Open Source (MIT License) for junior school home practice and games websites.
These are based on the old "SchoolHomework" project done by the author but done using more modern technologies and broken down into seperate microservices architecture.

## Author(s)
1. Hammad Rauf

## Repositories Included
1. SchoolShorts
2. SchoolDataAPI (RESTFull Persistence API)
3. MariaDB Database (Persistance Store)

## Architectural Dependencies (When Completed)
```
┌───────────────────────┐                          ┌────────────────────────┐
│                       │                          │                        │
│                       │                          │                        │
│                       │                          │                        │
│   SchoolShorts        │                          │   SchoolDataAPI        │
│   JAR/ Container      │                          │   JAR/ Container       │
│   Web Application     ├─────────────────────────►│   Web Application      │
│                       │                          │                        │
│                       │                          │                        │
│                       │                          │                        │
│                       │                          │                        │
└───────────────────────┘                          └────────────┬───────────┘
                                                                │
                                                                │
                                                                │
                                                                │
                                                                ▼
                                                 ┌───────────────────────────┐
                                                 │                           │
                                                 │                           │
                                                 │  MariaDB Database         │
                                                 │  JAR/ Container           │
                                                 │  Data Store               │
                                                 │                           │
                                                 │                           │
                                                 └───────────────────────────┘
```
