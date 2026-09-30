# GitHub Final Project

## Simple Interest Calculator

A simple command-line calculator that calculates the simple interest earned on a principal amount based on the annual rate of interest and the time period.

## Project Description

The Simple Interest Calculator is a Bash command-line application. It asks the user to enter three values:

* **Principal (P):** The initial amount of money.
* **Rate of Interest (R):** The annual interest rate, expressed as a percentage.
* **Time (T):** The amount of time the money is invested or borrowed, expressed in years.

The calculator uses the standard simple interest formula:

**Simple Interest = (P × R × T) / 100**

The calculated simple interest is then displayed in the terminal.

## How the Calculator Works

1. The user starts the `simple-interest.sh` Bash script.

2. The script asks the user to enter the principal amount.

3. The script asks for the annual rate of interest.

4. The script asks for the time period in years.

5. The script calculates simple interest using the formula:

   `SI = (P × R × T) / 100`

6. The calculated simple interest is displayed to the user.

## Usage

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/github-final-project.git
```

Move into the project directory:

```bash
cd github-final-project
```

Make the script executable:

```bash
chmod +x simple-interest.sh
```

Run the calculator:

```bash
./simple-interest.sh
```

## Example

Suppose the user enters:

```text
Principal: 1000
Rate of Interest: 5
Time: 2
```

The calculator applies:

```text
Simple Interest = (1000 × 5 × 2) / 100
```

The result is:

```text
Simple Interest = 100
```

Therefore, the simple interest on $1,000 at an annual interest rate of 5% for 2 years is **$100**.

## Input

The calculator requires three inputs:

| Input     | Description              | Example |
| --------- | ------------------------ | ------: |
| Principal | Initial amount           |    1000 |
| Rate      | Annual interest rate (%) |       5 |
| Time      | Time period in years     |       2 |

## Output

The program displays the calculated simple interest.

Example:

```text
Simple Interest: 100
```

## Formula

```text
SI = (P × R × T) / 100
```

Where:

* `SI` = Simple Interest
* `P` = Principal
* `R` = Rate of Interest
* `T` = Time in years

## Technologies Used

* Bash
* Git
* GitHub

## Project Structure

```text
github-final-project/
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
└── simple-interest.sh
```

## Contribution

Contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.

Please follow the project's contribution guidelines when submitting changes.
