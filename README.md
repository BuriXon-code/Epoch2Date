# Epoch2Date

Epoch2Date is a simple Bash script that converts an epoch timestamp into a human-readable date and time (UTC) without using the `date` command.

## Features
- Supports both positive and negative epoch timestamps.
- Outputs the result in `YYYY-MM-DD HH:MM:SS UTC` format.
- Displays the day of the week.
- Works entirely without `date`, performing all calculations manually.

## Installation

Clone the repository:
```bash
git clone https://github.com/BuriXon-code/Epoch2Date
cd Epoch2Date
```
Make the script executable:
```bash
chmod +x epochcalc
```

## Usage
Run the script with an epoch timestamp as an argument:
```bash
./epochcalc 1710445200
```
Example output:
```
Monday 2024-03-14 12:00:00 UTC
```
For negative timestamps (dates before 1970):
```bash
./epochcalc -1742169546
```
Example output:
```
Sunday 1914-10-18 01:24:54 UTC
```

## Notes
- If no argument is provided, the script should return an error message.
- Ensure you pass a valid numeric timestamp.

