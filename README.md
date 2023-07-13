# SecurePass

This is a simple password manager program written in Python. It allows you to store and view passwords securely using the cryptography library.

## Installation

1. Clone the repository or download the project files.
2. Install the required dependencies by running `pip install cryptography` in your command prompt or terminal.

## Usage

1. Run the `main.py` script.
2. Upon running the script, a key file (`key.key`) will be generated, which stores the encryption key for the passwords.
3. Choose one of the following options:
   - To add a new password, enter `add`, and provide the account name and password when prompted.
   - To view existing passwords, enter `view`.
   - To quit the program, enter `q`.
4. The passwords are stored in the `passwords.txt` file, encrypted using the Fernet encryption scheme.
5. Each line in the `passwords.txt` file represents an account name and its corresponding encrypted password, separated by a pipe (`|`).

## Security Considerations

- The encryption key is stored in the `key.key` file, which should be kept secure and not shared with others.
- Ensure that you have appropriate file permissions to protect the `key.key` and `passwords.txt` files.
- Use caution when storing or sharing the `passwords.txt` file, as it contains sensitive information (encrypted passwords).

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

