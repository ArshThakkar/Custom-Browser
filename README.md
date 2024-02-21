# Custom Browser

This project is a simple custom web browser built using PyQt5 library in Python. It provides basic functionalities like navigation, reloading, and accessing home page along with a URL bar for entering web addresses.

## Features

- **Navigation**: Navigate backward and forward through web pages.
- **Reloading**: Reload the current web page.
- **Home Page**: Navigate to the default home page.
- **URL Bar**: Enter and go to a specific web address.

## Requirements

- Python 3.x
- PyQt5 library

## Installation

1. Clone the repository or download the script.
2. Install PyQt5 library if not already installed:

   ```bash
   pip install PyQt5
   ```

3. Run the script using Python.

   ```bash
   python custom_browser.py
   ```

## Usage

- Use the back and forward buttons to navigate through the browser history.
- Click on the reload button to refresh the current web page.
- Press the home button to go to the default home page.
- Enter a web address in the URL bar and press Enter to navigate to that address.

## Customization

You can customize the default home page by modifying the `navigate_home` method in the code.

```python
def navigate_home(self):
    self.browser.setUrl(QUrl('http://your-default-homepage.com'))
```

## Note

- This is a basic implementation and may not support all features of modern web browsers.
- Ensure that you have an active internet connection to browse web pages.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, or suggest improvements via GitHub. Contributions are welcome!
