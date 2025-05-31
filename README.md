# Construction Landing Page Project

This project is a simple landing page built with HTML, CSS, JavaScript, and Bootstrap.

## Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge).
- A code editor (e.g., Visual Studio Code) if you want to edit the files.

## How to Run

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser to view the landing page.

## Project Structure

- `index.html`: The main HTML file for the landing page.
- `css/styles.css`: Custom CSS for styling the page.
- `js/scripts.js`: Custom JavaScript for interactivity.

## External Libraries

- [Bootstrap 5](https://getbootstrap.com/): Used for responsive design and prebuilt components.

## Customization

Feel free to modify the `css/styles.css` and `js/scripts.js` files to customize the design and functionality of the landing page.

## Custom Domain Setup (GoDaddy)

To use your GoDaddy domain (ozufer.com) with GitHub Pages:

1. In your GoDaddy DNS settings, add these A records for ozufer.com:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
2. For www.ozufer.com, add a CNAME record pointing to your GitHub Pages URL (e.g., your-username.github.io).
3. In this repository, ensure the CNAME file contains only:
   
   ```
   ozufer.com
   ```
4. Wait for DNS changes to propagate (can take up to 24 hours).

Your site will be served at https://ozufer.com once everything is set up.