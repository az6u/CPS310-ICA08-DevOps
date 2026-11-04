# Release Audit

## Project Description

Release Audit reads support-ticket data from the file configured in `config.json` and displays the tickets in a table. It also reports the total number of tickets, the number of open tickets, and the number of high-priority tickets using the configured threshold.

## Requirements

- Python 3.12 or newer
- Git
- Project dependencies listed in `requirements.txt`

## Setup Instructions

Open PowerShell and run:

1. Clone the repository:

   
   git clone https://github.com/az6u/CPS310-ICA08-DevOps.git
   

2. Change to the project directory:

   powershell
   cd CPS310-ICA08-DevOps
   

3. Create a virtual environment named `.venv`:

   powershell
   py -3.12 -m venv .venv
   

4. Activate the virtual environment:

   powershell
   .\.venv\Scripts\Activate.ps1
   

5. Install the project dependencies:

   powershell
   python -m pip install -r requirements.txt
   

## Run

With the virtual environment activated, run:

powershell
python release_audit.py

