# Selenium Automation Skill for OpenClaw

This repository contains a custom skill for OpenClaw. It allows your AI agent to perform advanced web automation using Python, Selenium WebDriver, and ChromeDriver.

## Features
* **Browser Setup:** Automatic configuration for headless Chrome.
* **Navigation:** Commands to open, refresh, and navigate web pages.
* **Screenshots:** Capture full pages or specific HTML elements.
* **JavaScript Injection:** Execute custom scripts directly in the browser.
* **Element Interaction:** Find elements, click buttons, and type text.

## Requirements
To use this skill, you need to have the following installed on your system:
* Python 3
* Selenium library
* ChromeDriver

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/frederickgzmn/selenium-automation.git](https://github.com/frederickgzmn/selenium-automation.git)
   ```

2. Move the folder to your OpenClaw skills directory:
   ```bash
   mv selenium-automation ~/.openclaw/skills/
   ```

3. Install the Selenium library for Python:
   ```bash
   pip install selenium
   ```

4. Install ChromeDriver. If you use macOS, you can use Homebrew:
   ```bash
   brew install chromedriver
   ```
   If you use Linux (like Fedora or Ubuntu), you can use your package manager (for example, `sudo dnf install chromedriver` or `sudo apt install chromium-chromedriver`).

## Usage

Once the installation is complete, you can ask your OpenClaw agent to perform web tasks. For example, you can tell it:

> "Use your Selenium skill to open example.com, extract the main heading, and take a screenshot of the page."

The agent will read the instructions in the `SKILL.md` file. Then, it will automatically write and run the Python code to complete the task.

## License
MIT License
