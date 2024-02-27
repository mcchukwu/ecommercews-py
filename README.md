# ecommercews-py

## Overview

This is a python implementation of a web scrapper that extracts product details from an ecommerce website.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/mcchukwu/ecommercews-py.git
    cd ecommercews-py
    ```

2. Set up a virtual environment and install dependencies:

    ```bash
    python -m venv venv
    venv\Scripts\activate  # On Windows
    pip install -r requirements.txt
    ```

3. Edit `main.py` with the desired product URL.

4. Run the `main.py` script:

    ```bash
    python main.py
    ```

## Project Structure

project_root/

│

├── scraper/

│ ├── init.py

│ ├── e_commerce_scraper.py

│

└── main.py

- **`scraper/`**: Contains the web scraper module.
  - **`e_commerce_scraper.py`**: Implements the ecommerce scrapper class for scraping product data.

- **`main.py`**: Example script demonstrating how to use the scraper.

## Dependencies

- [requests](https://docs.python-requests.org/en/master/)
- [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
