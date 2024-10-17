# localStorage
# LocalStorage Enquiry Form

This project is a simple web-based enquiry form that uses `localStorage` to store user details like name, email, and phone number. The data is displayed dynamically, and users can remove individual entries or clear all data at once.

## Features
- Users can submit their **Name**, **Email**, and **Phone Number** through a form.
- Data is validated to prevent duplicate email addresses or phone numbers.
- User details are stored in the browser's `localStorage` and persist across page reloads.
- Entries are displayed dynamically on the page.
- Users can:
  - Remove individual entries.
  - Clear all entries with a single button.

## Technologies Used
- **HTML**: Structuring the web page.
- **CSS**: Basic styling for the form and displayed data.
- **JavaScript**: Handling form submission, validation, data manipulation, and interactions with `localStorage`.

## How to Use

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/surya391/localstorage-enquiry-form.git
    ```

2. **Navigate to the Project Directory:**
    ```bash
    cd localstorage-enquiry-form
    ```

3. **Open the Project in Your Browser:**
    Simply open the `index.html` file in your browser to view the form and start adding data.

## Functionality

- **Submit Enquiry:**
    - Fill out the **Name**, **Email**, and **Phone** fields.
    - Upon clicking "Save," the details are saved to `localStorage` if the email or phone number doesn't already exist.

- **Remove Entries:**
    - Each entry is displayed with a "×" button that allows for removing individual records.

- **Clear All Data:**
    - A "Clear All" button at the bottom of the page deletes all saved data from `localStorage`.

## LocalStorage Management
The project uses `localStorage` to manage user data:
- Data is stored as a JSON array of objects containing user **name**, **email**, and **phone**.
- Upon form submission, the data is checked for duplicates (either email or phone).
- The user can either remove individual entries or clear all entries.

## Future Enhancements
- Add form validation to ensure proper email and phone formats.
- Display error messages directly on the form instead of using `alert()`.
- Allow for editing of existing records.
- Make the layout responsive for mobile devices.

## License
This project is open-source and available under the [MIT License](LICENSE).
