# E-Commerce_Back_End

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---
## Description

This is an e-commerce backend built from starter code. It uses [MySQL2](https://www.npmjs.com/package/mysql2), [Sequelize](https://www.npmjs.com/package/sequelize), [Express.js](https://www.npmjs.com/package/express), and the [dotenv](https://www.npmjs.com/package/dotenv) package.
  

---
## Table of Contents

  - [Installation](#installation)
  - [Usage](#usage)
  - [Tests](#tests)
  - [Contribute](#contribute)
  - [Credits](#credits)
  - [License](#license)


---
## Installation

In order to use this application, you could clone the repo and run it in the terminal using ```node server.js```. 

- [E-Commerce Back-end Git Hub Repository](https://github.com/areitan/E-Commerce_Back_End)
- [E-Commerce Back-end Walkthrough Video Link](https://drive.google.com/file/d/12Ciy8ch7IybVs9cHZsS1iRlog9jFPtTc/view)


---
## Usage

In order to use this application: 

1. Clone the repo. 
2. In MySQL, run ```source db/schema.sql```
3. Exit MySQL once the schema has successfully been sources.
4. Run ```npm run seed``` to bring in the seed data.
4. In the terminal run```node server.js``` to start the server.

### Install Schema
![E-Commerce Back-end Install Schema](/assets/1_schema.png)

### Run Seed Data
![E-Commerce Back-end Run Seed Data](/assets/2_seed.png)

### Start Server
![E-Commerce Back-end Start Server](/assets/3_start_server.png)

### An example of a successful test (Please watch walk-through video above to see all tests)
![E-Commerce Back-end successful test](/assets/4_tests.png)

---
## Tests

The GET, PUT, POST and DELETE routes were tested for Categories, Products, and Tags using Insomnia. (Please watch walk-through video above to see all tests run.

### E-Commerce Back-end Mock-ups Provided
![E-Commerce Back-end Mock-up 1](/assets/13-orm-homework-demo-01.gif)
![E-Commerce Back-end Mock-up 1](/assets/13-orm-homework-demo-02.gif)
![E-Commerce Back-end Mock-up 1](/assets/13-orm-homework-demo-03.gif)


--- 
## Contribute

In order to create this application, I used the skills I have at the moment. I am open to suggestions, if there are ways to streamline the code or if any bugs are found.

---
## Credits

- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [Express.js](https://www.npmjs.com/package/express)
- [dotenv](https://www.npmjs.com/package/dotenv) package.
- Trilogy Education Services, LLC for the starter code, example code throughout the week 13 exercises, and example mock-up.
- Chris Baird, my tutor


### Questions

For any question, please contact me on GitHub at: [areitan](https://github.com/areitan) or by email at <areitan@fredhutch.org>.

---

## License

Copyright (c) ```<2022> <copyright April Reitan>```

MIT License:
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.