
# Flutter Application: Booking History

This Flutter application fetches and displays booking history details from a remote API. The app presents the data in a list view with a simple user interface.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview

The application is designed to fetch user data from `https://jsonplaceholder.typicode.com/users` and display it in a card format. Each card contains user information such as name, email, city, phone, and website.

## Features

- Fetches data from a remote API.
- Displays user data in a card format.
- Shows a loading indicator while fetching data.

## Installation

To install and run this application, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone "https://github.com/kri-sh03/BookingHistory.git"
   cd <repository-directory>
   ```

2. **Install Flutter:**

   Follow the instructions to install Flutter from the official [Flutter website](https://flutter.dev/docs/get-started/install).

3. **Install dependencies:**

   ```sh
   flutter pub get
   ```

4. **Run the application:**

   ```sh
   flutter run
   ```

## Usage

1. **Launch the application:**
   Open the terminal and navigate to the project directory. Run the command `flutter run` to launch the application.

2. **View booking history:**
   The application will automatically fetch the user data from the API and display it in a list view. Each card contains the following details:
   - Name
   - Email
   - City
   - Phone
   - Website

3. **Loading indicator:**
   While the data is being fetched, a circular progress indicator will be displayed. Once the data is fetched, the list of user details will be shown.

## Dependencies

This application uses the following dependencies:

- `flutter`: SDK for building mobile applications.
- `http`: Package for making HTTP requests.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b my-feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin my-feature-branch`.
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
