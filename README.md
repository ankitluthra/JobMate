## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Python 3.x
- Google Chrome (or another supported browser)
- ChromeDriver (or the appropriate WebDriver for your browser)

### Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/jobmate.git
   cd jobmate
   ```

2. **Create a virtual environment:**
    ```
    python3 -m venv jobmate_env
    source jobmate_env/bin/activate  # On Windows: jobmate_env\Scripts\activate
    ```

3. **Install required packages:**
    ```pip install -r requirements.txt```

4. **Download and install ChromeDriver:**
    Download ChromeDriver
    Place the downloaded chromedriver executable in your system PATH or in the project directory.

    Why we need ChromDriver?
    When we use Selenium for browser automation with Python, we need ChromeDriver (or another WebDriver for chosen browser) to interact with the browser programmatically.

### Running the Project
    Activate the virtual environment:
    source jobmate_env/bin/activate  # On Windows: jobmate_env\Scripts\activate

### Run the main script:
    python main.py

### Contributing
    If you'd like to contribute to JobMate, please follow these steps:

### Fork the repository
    1. Create your feature branch (git checkout -b feature/your-feature)
    2. Commit your changes (git commit -m 'Add your feature')
    3. Push to the branch (git push origin feature/your-feature)
    4. Create a pull request

### License
    See the LICENSE file for details.

### Acknowledgments (Ideas on tools that we can use)
    Selenium for browser automation
    Beautiful Soup for web scraping
    Requests for making HTTP requests
    Pandas for data manipulation
    Schedule for job scheduling