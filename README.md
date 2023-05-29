# true_beacon

## Overview

A simple react project that shows the prices of NIFTY 50 and NIFTY Bank for the range of dates provided using the golang backend service connected to mysql server.
## Table of Contents

- [true\_beacon](#true_beacon)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
- [Backend](#backend)
  - [Installation](#installation)
- [Frontend](#frontend)
  - [Installation](#installation-1)
  - [Folder Structure](#folder-structure)
- [Contributing](#contributing)

# Backend


## Installation

1. Ensure you have Go installed on your machine. If not, you can download and install it from the [official Go website](https://golang.org/dl/).

2. Clone the repository:

   ```shell
   git clone https://github.com/your-username/your-repository.git
   ```

3. Change to the project directory:

   ```shell
   cd your-repository
   ```

4. Install the dependencies:

   ```shell
   go mod download
   ```
5. Change the mysql setup

   In the file `/backend/utility/sql.go`

   **Replace the "password" in the db URI with the password of the root user to your mysql server.**

6. Build the project:

   ```shell
   go build
   ```

# Frontend


## Installation

1. Ensure you have Node.js installed on your machine. If not, you can download and install it from the [official Node.js website](https://nodejs.org).

2. Clone the repository:

   ```shell
   git clone https://github.com/your-username/your-repository.git
   ```

3. Change to the project directory:

   ```shell
   cd your-repository
   ```

4. Install the dependencies:

   ```shell
   npm install
   ```

5. Start the development server:

   ```shell
   npm start
   ```

   This command will start the development server and open the project in your default browser.



## Folder Structure

```
├── public
├── src
│   ├── components
│   │   ├── DateInput.tsx
│   │   ├── Dropdown.tsx
│   │   ├── Graph.tsx
│   │   ├── InputData.tsx
│   │   └── LineGraph.tsx
│   ├── App.tsx
│   ├── index.tsx
│   └── styles.css
├── .gitignore
├── package.json
├── tsconfig.json
├── README.md
└── LICENSE
```

# Contributing

Contributions are welcome! If you find a bug or have an idea for an improvement, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```shell
   git checkout -b feature/your-feature
   ```

3. Make your changes and commit them:

   ```shell
   git commit -m "Your commit message"
   ```

4. Push the changes to your forked repository:

   ```shell
   git push origin feature/your-feature
   ```

5. Open a pull request on the original repository and describe your changes.


# Screenshots

![image](https://github.com/ArshpreetS/true_beacon/assets/76895787/07931eb7-597f-486d-bcf5-db1b92f8778e)

