# Bankist App

The Bankist App is a simple, front-end banking application simulation built with HTML, CSS, and vanilla JavaScript. It demonstrates various modern JavaScript concepts, including array methods, event handling, and functional programming techniques, to manage user accounts and transactions.

##  Features

The application simulates a basic banking interface with the following core functionalities:

*   **User Authentication:** Log in using hardcoded usernames and PINs.
*   **Account Overview:** Displays the current balance and a list of all transaction movements (deposits and withdrawals).
*   **Transaction Summary:** Calculates and displays the total income, total outgoing, and accrued interest for the current account.
*   **Money Transfer:** Allows users to transfer funds to another existing account.
*   **Loan Request:** Users can request a loan, which is approved if the account has at least one deposit of at least 10% of the requested loan amount.
*   **Account Closure:** Users can close their account by confirming their username and PIN.
*   **Sorting:** Movements can be sorted in ascending or descending order.
*   **Logout Timer:** A simple timer is implemented to automatically log the user out after a period of inactivity.

##  Technologies Used

*   **HTML5**
*   **CSS3**
*   **JavaScript (ES6+)**

##  Login Credentials

The application uses hardcoded data for demonstration purposes. You can log in with the following credentials:

| Owner | Username | PIN |
| :--- | :--- | :--- |
| Jonas Schmedtmann | `js` | `1111` |
| Jessica Davis | `jd` | `2222` |
| Steven Thomas Williams | `stw` | `3333` |
| Sarah Smith | `ss` | `4444` |

*Note: The username is generated from the owner's initials (e.g., **J**onas **S**chmedtmann -> `js`).*

## 💻 How to Run

This is a purely front-end application and does not require any build tools or server-side setup.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Yiranubari/Bankist.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Bankist
    ```
3.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser.

##  Project Structure

```
Bankist/
├── index.html          # Main application structure
├── style.css           # Styling for the application
├── script.js           # Core JavaScript logic and functionality
├── logo.png            # Application logo asset
├── icon.png            # Favicon asset
└── Bankist-flowchart.png # Flowchart/diagram of the application logic
```

##  Learning Focus

This project is an excellent resource for learning and practicing:

*   Advanced JavaScript array methods (`map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `every`, `flat`, `flatMap`, `sort`).
*   DOM manipulation and event handling.
*   Implementing a simple user interface with modern CSS layouts.
*   Functional programming paradigms in JavaScript.
*   Simulating real-world application logic (transfers, loans, account management).
