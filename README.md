# Budget-Tracker


## Description

I want to give users a fast and easy way to track their money with the ability to access that information at any time. I added functionality to an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the total should be updated when the application is brought back online.



## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployed Site](#deployed-app)
- [Tech Used](#tech-used)
- [Contact](#contact)
- [License](#license)
- [Contributing](#contact)


```md
GIVEN a Budget Tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```


## User Story

```md
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```


## Deployed App

[Heroku Link to Deployed Site](https://polar-hollows-87169.herokuapp.com/)

<img src="https://user-images.githubusercontent.com/87335354/144963500-5c027b52-573e-4349-aab0-b90f0d4c68ed.png" width="600">


## Installation
1. Download or clone repository
2. `npm install` to install the required npm packages to run

## Usage
* Application will be invoked by using the following command:

  `node server.js`

* Open your browser and go to
  
  `http://localhost:3000`

* User can add transactions as deposits or expenses by inputting the following:
  * Name of transaction
  * Transaction amount
  * For deposits - select **Add Funds**
  * For expenses - select **Subtract Funds**

* The total amount is reflected as soon as funds are entered

* The graph portrays the total funds over time by date entered for each transaction

## Tech Used

`IndexedDB`

`service worker`

`Express.js`

`MongoDB`

`Mongoose`

Deployment to Heroku Using `MongoDB Atlas`


## Contact

[Pamela](https://github.com/pamelac21)[![GitHub](https://img.shields.io/badge/--181717?logo=github&logoColor=ffffff)](https://github.com/)

[Email me](pamelac021@gmail.com)



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
