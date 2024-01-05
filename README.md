# Chrome Password Decryptor

This script decrypts saved passwords from Google Chrome on a local machine. It utilizes the Chrome local state file and the login database to extract and decrypt the passwords.

## Prerequisites

Before running the script, ensure that you have the following prerequisites installed:

- Python 3.x
- Required Python packages (install using `pip install -r requirements.txt`)

## Usage

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/chrome-password-decryptor.git
    cd chrome-password-decryptor
    ```

2. **Run the script:**

    ```bash
    python chrome_password_decryptor.py
    ```

    The script will prompt you to enter the Chrome user profile (e.g., "Default" or "Profile1") from which you want to decrypt passwords.

## Output

The script will create a CSV file named `decrypted_password.csv` containing the decrypted passwords, along with the corresponding URLs and usernames.

## Important Note

- This script may not work for Chrome versions older than 80.

## Contributing

If you'd like to contribute to this project, please follow the standard GitHub flow:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Create a pull request.

## Issues

If you encounter any issues or have suggestions, please open an issue on GitHub.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
