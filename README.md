# InvestCalc

InvestCalc is a React-based investment calculator that allows users to input key details about their investment plans—such as initial investment, annual contributions, expected return, and duration. The tool then calculates the investment's value over time, displaying the yearly growth, interest, and total invested capital.

## Features

- **User Inputs**:
  - **Initial Investment**: The starting amount invested.
  - **Annual Investment**: The amount added to the investment every year.
  - **Expected Return**: The expected annual return rate (in percentage).
  - **Duration**: The number of years you plan to invest.
- **Dynamic Calculation**:

  - Displays yearly data such as:
    - **Investment Value**: The value of the investment for each year.
    - **Interest (Year)**: The interest earned in that year.
    - **Total Interest**: The total interest earned over the investment period.
    - **Invested Capital**: The cumulative amount of capital contributed over time.

- **React State Management**:

  - Uses React's state and props to dynamically update the table of investment data each time the input changes.

- **User-Friendly Interface**:
  - Easy-to-understand inputs and automatic calculation on changes.

## Technologies Used

- **React**: For building the user interface and managing state.
- **HTML**: For structuring the page content.
- **CSS**: For styling the application and making it responsive.
- **JavaScript (ES6+)**: For implementing the core logic of investment calculations.

## How to Use

1. Open the `index.html` file in your browser or run the app locally after setting up the React app.
2. Enter the following details:
   - **Initial Investment**: The amount you start with.
   - **Annual Investment**: The amount you add to your investment each year.
   - **Expected Return**: The expected annual return rate (e.g., 5% for a 5% return).
   - **Duration**: The number of years you will keep investing.
3. The app will display a table showing:
   - **Year**: The year of the investment.
   - **Investment Value**: The value of the investment at the end of that year.
   - **Interest (Year)**: The interest earned for that year.
   - **Total Interest**: The total interest accumulated so far.
   - **Invested Capital**: The total amount you've contributed.

## Sample Output Table

| Year | Investment Value | Interest (Year) | Total Interest | Invested Capital |
| ---- | ---------------- | --------------- | -------------- | ---------------- |
| 1    | $1,000.00        | $50.00          | $50.00         | $1,000.00        |
| 2    | $1,050.00        | $52.50          | $102.50        | $2,000.00        |
| 3    | $1,102.50        | $55.13          | $157.63        | $3,000.00        |

## Getting Started

### Prerequisites

- Ensure you have **Node.js** and **npm** or **yarn** installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/visheshparab/investcalc.git
   ```
