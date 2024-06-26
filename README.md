# Horizon Bank Web Application

Welcome to Horizon Bank Web Application! This project aims to provide users with a seamless and secure online banking experience. Below you'll find information on different pages and functionalities implemented in this application.

## Dashboard Page (homepage.php)

The dashboard page serves as the central hub for Horizon Bank's online banking platform. It provides users with an overview of their account information and quick access to various banking functionalities.

![Dashboard Page](assets/images/home_page.png)

### Features:
- **User Dashboard:** Upon logging in, users are redirected to the dashboard, which displays their account details such as account number, name, and balance.
- **Navigation:** Users can easily navigate to different sections of the banking platform using the navigation menu located at the top of the page.
- **Functional Links:** The dashboard provides links to essential banking functionalities such as viewing favorites, transferring funds, paying bills, and generating bank statements.
- **Responsive Design:** The dashboard is designed to be responsive, ensuring optimal viewing and interaction across different devices and screen sizes.
- **Customizable Content:** The dashboard content can be customized to include additional features or personalized information based on user preferences.
- **Logout Option:** Users can securely logout from their account using the "Sign Out" link located in the navigation menu.

## Login Page (bank_login.php)

The login page allows registered users to securely log in to their Horizon Bank accounts. Users are required to enter their username and password to access their account dashboard.

![Login Page](assets/images/login_page.png)

### Features:
- Secure login functionality with session management.
- Account blocking mechanism after multiple failed login attempts.
- Form validation for user input.

## Favorite Page (favorites.php)

The favorite page allows users to save their frequently used transactions or beneficiaries for quick access. It provides a convenient way for users to perform recurring transactions without entering the details repeatedly.

![Favorites Page](assets/images/favourites_page.png)

### Features:
- Add, edit, and delete favorite transactions or beneficiaries.
- Quick access to saved favorites for fund transfers and bill payments.

## Transfer Funds Page (bank_transferfunds.php)

The transfer funds page enables users to transfer money between their accounts or to other beneficiaries. Users can specify the recipient's account details, transfer amount, and authorize the transaction using their PIN.

![Transfer Funds Page](assets/images/transfer_funds_page.png)

### Features:
- Secure fund transfer functionality with PIN authorization.
- Validation to ensure sufficient balance and correct PIN entry.
- Form for entering transfer details.

## Pay Bills Page (bank_paybills.php)

The pay bills page allows users to make payments for various bills directly from their Horizon Bank accounts. Users can select the recipient, enter the payment amount, and authorize the transaction using their PIN.

![Pay Bills Page](assets/images/pay_bills_page.png)

### Features:
- Secure bill payment functionality with PIN authorization.
- Validation to ensure correct recipient selection and sufficient balance.
- Form for entering bill payment details.

## Generate Bank Statement Page (bank_statement.php)

The generate bank statement page provides users with a summary of their account transactions over a specified time period. Users can view their account balance, deposits, withdrawals, and other transaction details.

![Generate Bank Statement Page](assets/images/generate_bank_statement_page.png)

### Features:
- Retrieve transaction history from the database based on user input.
- Form for specifying the start date of the bank statement.
- Display transaction details in a table format.

## Contributors

This project was developed by a team of talented developers passionate about delivering a user-friendly and secure online banking experience.

- John Doe (@johndoe)
- Jane Smith (@janesmith)
- Alex Johnson (@alexjohnson)
