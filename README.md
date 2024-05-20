# Bank Management System

Welcome to the Bank Management System! This is a user-friendly web application built with Python and Streamlit, designed to facilitate various banking operations with ease and efficiency. Whether you're a bank administrator or an account holder, this system offers a range of features to manage your banking needs.

## Features

### For Account Holders

- **Create Account**: Easily open a new bank account by providing your name, age, and gender.
- **Deposit**: Deposit money into your account swiftly.
- **Withdraw**: Withdraw funds from your account securely.
- **Check Balance**: Instantly check your account balance anytime.
- **Transaction History**: View a detailed history of all transactions made on your account.

### For Bank Administrators

- **View All Accounts**: Access comprehensive details of all accounts, including account number, name, age, gender, and balance.
- **Delete Account**: Remove accounts as per administrative requirements.

## Technologies Used

- **Python**: The backbone of our application, providing robust and efficient logic.
- **SQLite**: A lightweight and reliable relational database for storing account and transaction data.
- **Streamlit**: A modern Python library for building interactive and visually appealing web applications.

## How to Run

### Prerequisites

Ensure you have Python and pip installed on your system.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/bank-management-system.git
    cd bank-management-system
    ```

2. Install the required dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Application

1. Run the Streamlit application:
    ```bash
    streamlit run bank_management.py
    ```

2. Open your web browser and navigate to the provided URL (typically [http://localhost:8501](http://localhost:8501)).

## File Structure

- **bank_management.py**: The main Python script containing the implementation of the Bank Management System.
- **bank.db**: The SQLite database file storing account and transaction data. This file is auto-generated upon running the application for the first time.
- **requirements.txt**: A text file listing the necessary Python dependencies.
- **README.md**: This file providing an overview and detailed description of the Bank Management System.

## User Interface

The user interface is designed to be intuitive and easy to navigate. Here's a quick look at the main sections:

- **Sidebar Menu**: Navigate between different functionalities like creating accounts, viewing transaction history, and more.
- **Main Panel**: Interact with the chosen functionality, input necessary details, and view results and feedback.

## Contributors

- **Guru Krithick**
    - Email: krithickguru13@gmail.com
    - GitHub: [guru-krithick](https://github.com/guru-krithick)

We welcome contributions to this project! Feel free to submit bug reports, feature requests, or pull requests on our [GitHub repository](https://github.com/your-repo/bank-management-system).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
