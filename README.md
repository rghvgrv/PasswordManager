# Password Manager 

A simple Python-based Password Manager that allows you to store, retrieve, and manage your passwords securely.

## Features

- **Password Storage**: Save credentials securely in a local file.
- **Encryption**: This uses encryption for better security (the key is stored in the `key.key` file).
- **Command-line Interface**: Easy-to-use CLI for adding, retrieving, and managing passwords.

## Prerequisites

- Python 3.x installed on your system.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/rghvgrv/PasswordManager.git
   cd PasswordManager
   ```

2. Ensure you have the necessary Python libraries installed:
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is missing, ensure libraries like `cryptography` are installed manually.)*

## Usage

1. Run the main script:
   ```bash
   python main.py
   ```

2. Follow the prompts to:
   - Add a new password.
   - Retrieve stored passwords.
   - Manage existing entries.

## File Details

- **`main.py`**: Core application logic.
- **`key.key`**: Encryption key for securing passwords.
- **`password.txt`**: Stores encrypted password data.
- **`tempCodeRunnerFile.py`**: Temporary development file (can be ignored).

## Security Notice

- Ensure the `key.key` file is stored securely and not shared. Losing this file will result in an inability to decrypt stored passwords.

## Contribution

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-branch
   ```
5. Submit a pull request.

## License

This project is open-source and available under the [MIT License](LICENSE).
```
