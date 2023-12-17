# Google Chrome Automation on Replit

## Overview

This repository contains a Python script that leverages Selenium to automate interactions with Google's search engine on Replit.com. The script utilizes the Chrome web browser for automation and includes functionality to save and restore cookies and LocalStorage data.

## Prerequisites

Before running the script, ensure you have the following:

- Python installed (version 3.x recommended)
- Chrome web browser installed
- ChromeDriver compatible with your Chrome version. You can download ChromeDriver from [here](https://sites.google.com/chromium.org/driver/)

## Setup

1. Clone the repository to your local machine:

```bash
git clone https://github.com/jeet-programmer/google-chrome-on-replit.git
cd google-chrome-on-replit
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Download ChromeDriver and place it in the project directory.

## Usage

1. Open the `main.py` file and set the `SINGLE_PAGE` variable to the desired website URL (e.g., "https://google.com").

2. Run the script:

```bash
python main.py
```

3. The script will open a Chrome browser, navigate to the specified URL, perform Google search (if applicable), and save cookies. You can stop the script at any time, and it will save the current state.

## Features

- **Cookie Management:** The script can save and load cookies to maintain the session state across runs.
- **LocalStorage Handling:** LocalStorage data can be saved and restored for web pages (configured through `SINGLE_PAGE`).

## Troubleshooting

- If you encounter issues, ensure that ChromeDriver is compatible with your Chrome version.
- Check the console output for error messages.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to improve the script or add new features.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code.
