# Frontend Mentor - Tip calculator app

![Design preview for the Tip calculator app coding challenge](./preview.jpg)

The app allows users to calculate the tip and total amount per person by entering a bill amount, selecting a tip percentage, and entering the number of people.

## Features

- Calculate tip amount per person
- Calculate total amount per person
- Select predefined tip percentages:
  - 5%
  - 10%
  - 15%
  - 25%
  - 50%
- Enter a custom tip percentage
- Validate the number of people
- Display an error when the number of people is zero
- Reset the calculator
- Responsive design for mobile, tablet, and desktop
- Interactive button and input states
- Accessible form controls and focus states

## Built With

- HTML5
- TypeScript
- Tailwind CSS
- Vite

## How It Works

The calculator uses the following formulas:

### Tip Amount

```text
Tip = Bill × (Tip Percentage ÷ 100)
