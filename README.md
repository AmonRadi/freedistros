# freedistros

## Description
A simple CLI tool to scrape links to fully free GNU/Linux distributions as confirmed by the Free Software Foundation (FSF).

## Features

- Lists GNU/Linux distros:
  - For PCs and workstations
  - For devices with limited resources
  - Historical entries no longer recommended by FSF
- Outputs to terminal or saves to timestamped `.txt` files
- Quiet mode for scripting
- Easy-to-use CLI

## Requirements

- Python 3.7+
- Python packages:
  - `requests`
  - `bs4`
  - `lxml`
  
  Install dependencies via:
    
    ```pip install requests bs4 lxml```

## Usage

  freedistros --for-pc

  freedistros --small

  freedistros --all --save /home/user/results --quiet

## CLI Options

  freedistros --help

## Installation

### Option 1:Clone and Run
	git clone https://github.com/AmonRadi/freedistros.git
	cd freedistros
	python3 freedistros

### Option 2: Install as CLI Tool
  Make it globally avaliable:

	sudo cp freedistros /usr/local/bin
	sudo chmod +x /usr/local/bin/freedistros

  Then run from anywhere:

	freedistros --all

## License

GNU GPLv3 [https://www.gnu.org/licenses/gpl-3.0.html.en]

## P.S.
I wrote this program as a lab work, but I'll be glad if it turns out useful for your projects.
If this tool was helpful or you have any feedback, feel free to mail me:
        4m0n.ra.666@gmail.com



