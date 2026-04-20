![Uploading Gemini_Generated_Image_gnpcpvgnpcpvgnpc.png…]()

# Samax Contacts Vault Ultimate

Samax Contacts Vault Ultimate is a fast, responsive, and completely offline contact management application. Built with vanilla web technologies, it provides a premium, minimalist interface for managing personal and professional connections without relying on external databases or backend services.

## Features

* **Local Storage Integration:** All contact data is securely saved in the browser's local storage, ensuring privacy and offline functionality.
* **CSV Import & Export:** Easily migrate your contacts in and out of the application using standard CSV files.
* **Smart Duplicate Merging:** Automatically detect and merge duplicate contacts based on matching names.
* **Custom Data Fields:** Add dynamic, custom key-value pairs to any contact for flexible record-keeping.
* **Advanced Sorting & Filtering:** Filter contacts by group labels, search across all fields, and sort alphabetically, by creation date, or by favorites.
* **Bulk Actions:** Select multiple contacts for quick deletion or management.
* **Zero Dependencies:** Built entirely with HTML5, CSS3, and Vanilla JavaScript. No frameworks or external libraries required.

## Tech Stack

* HTML5 (Structure)
* CSS3 (Custom responsive grid and modal system)
* Vanilla JavaScript ES6+ (Logic and Local Storage Management)

## Project Structure

The application follows standard web development practices with separated concerns:
* `index.html` - The main user interface and layout.
* `styles.css` - All visual styling and responsive design rules.
* `app.js` - The core application logic and data handling.

## Getting Started

1. Clone this repository to your local machine or download the files.
2. Ensure `index.html`, `styles.css`, and `app.js` are located in the same folder.
3. Open `index.html` in any modern web browser.
4. Start adding contacts or import an existing CSV file.

## Usage Notes

Since this application utilizes the browser's `localStorage` API, your data will persist across sessions on the same device and browser. Clearing your browser data will wipe the contacts unless they have been exported to a CSV file first. It is highly recommended to regularly export your contacts for backup purposes.

## License

This project is licensed under the MIT License.
