# Python Password Generator

This project is a simple yet powerful password generator application built using Python and Tkinter. It enables users to generate secure passwords of desired lengths with options to include or exclude character repetition.

---

## Features

- **Customizable Length**: Users can specify the desired length of the password.
- **Repetition Control**: Allows users to choose whether to include repeated characters in the password.
- **User-Friendly Interface**: Built using Tkinter for a simple and intuitive graphical user interface.
- **Instant Display**: Generated passwords are displayed in a read-only text box for easy copying.

---

## Installation

### Prerequisites
1. Python 3.7+
2. Required Libraries:
   - `tkinter`
   - `random`

### Setup Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/password-generator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd password-generator
   ```
3. Run the script:
   ```bash
   python password_generator.py
   ```

---

## Usage

1. Launch the application.
2. Enter the desired password length.
3. Choose repetition preference:
   - Enter `1` to disallow repetition.
   - Enter `2` to allow repetition.
4. Click on "Generate Password" to create a secure password.
5. The generated password will appear in the designated display area.

---

## Code Structure

### `password_generator.py`
The main script for the application, containing:
- Password generation logic using the `random` module.
- User interface design and functionality with Tkinter.

---

## Dependencies

- `random`: For generating random characters.
- `tkinter`: For building the graphical user interface.

---

## Future Improvements

- Add support for user-defined character sets (e.g., only letters, only numbers).
- Implement a strength meter to evaluate the generated password's security.
- Add a button to copy the password directly to the clipboard.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any bug fixes, feature suggestions, or enhancements.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.


