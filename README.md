# Redi-Frontend-Angular

<a href="https://github.com/Tengilimm/Redi-Backend">here for backend</a>


# <p align="center">RentMax Redi</p>

RentMax is a car rental web application. It allows users to view, review and rent vehicles in the system.

**NOTE: The data in the project images are fake data. The data in this picture are sample content prepared to promote the web application.**


## Contents
- [Features](#features)
- [Getting Started](#getting-started)
  * [Installation](#installation)
- [Tech Stack](#tech-stack)
- [Associated Project](#associated-project)
- [Contributions](#contributions)



## Features

+ If the user requests, the logged in e-mail is remembered
+ If the user's token period has expired, the system is automatically logged out
+ Users can view and update their information
+ Vehicles can be filtered by vehicle properties
+ Other cars of the brand are shown on the car detail page
+ Access to unauthorized pages is blocked with role-based authorization
+ Users can review and confirm the order while completing the order
+ When the user confirms the order, it is checked in the backend whether they have enough findex points to rent that vehicle. If the user's findex score is sufficient, he can rent the vehicle

## Getting Started

The project needs a backend to run properly. So first of all, review and install [RentMax-backend](https://github.com/Tengilimm/Redi-Frontend).

### Installation

1. Clone the repo
   ```sh
https://github.com/Tengilimm/Redi-Frontend.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run
   ```sh
   ng serve
   ```

## Tech Stack
| Technology / Library | Version |
| ------------- | ------------- |
| Angular | 12.2.4 |
| Angular Material | 12.2.6 |
| Bootstrap | 5.1.0 |
| Jquery | 3.6.0 |
| rxjs | 6.6.0 |
| auth0/angular-jwt | 5.0.2 |
| ngx-mask | 12.0.0 |
| ngx-spinner | 12.0.0 |
| ngx-toastr | 14.1.3 |

## Associated Project

The backend of this project [RentMaxRedi-backend](https://github.com/Tengilimm/Redi-Backend)

## Contributions

Thanks to dear [Engin Demiroğ](https://github.com/engindemirog) for his contributions.
