# Run Fooocus with Ease

This repository provides a simple script to clone and run the [Fooocus](https://github.com/lllyasviel/Fooocus) project.

## Requirements

- Python environment
- pip package manager

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/ainexus1/RunFooocus.git
   cd RunFooocus

2. Install dependencies and run the script:
   ```bash
   python runfooocus.py

## Example Python Script

- run_fooocus.py:
  ```bash
  # Install pygit2
  !pip install pygit2==1.15.1

  # Clone the Fooocus repository
  !git clone https://github.com/lllyasviel/Fooocus.git

  # Change directory to Fooocus
  %cd /content/Fooocus

  # Run the script
  !python entry_with_update.py --share --always-high-vram
## Options  
The script runs Fooocus with the following options: 
- `--share`: Enables sharing mode.
- `--always-high-vram`: Ensures high VRAM usage.

For more details and updates, visit the [Fooocus GitHub page](https://github.com/lllyasviel/Fooocus).
