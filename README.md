# Photo Booth App

A simple photo booth application built with Node.js and Express. This app allows users to upload photos and displays the uploaded photos on the same page.

## Features

- Upload photos in JPEG, JPG, PNG, or GIF formats.
- Displays the uploaded photo on the page.
- Alerts users if the uploaded file is not an image.

## Prerequisites

- Node.js and npm installed on your machine.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Sugamdeol/photo-booth-app.git
   cd photo-booth-app
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the application:**

   ```bash
   npm start
   ```

4. **Open your browser and go to:**

   ```plaintext
   http://localhost:3000
   ```

## File Structure

```
photo-booth-app
├── node_modules
├── public
│   └── style.css
├── uploads
├── views
│   └── index.ejs
├── .gitignore
├── package.json
├── package-lock.json
└── server.js
```

## Explanation of Files

- **public/style.css**: Contains the CSS for styling the frontend.
- **uploads/**: Directory where uploaded photos are stored.
- **views/index.ejs**: The main HTML template for the photo booth app.
- **.gitignore**: Specifies which files and folders Git should ignore.
- **package.json**: Contains metadata about the project and its dependencies.
- **server.js**: The main server file where the Express server is set up and configured.

## Technologies Used

- Node.js
- Express
- Multer
- EJS

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## Acknowledgements

- [Express](https://expressjs.com/)
- [Multer](https://github.com/expressjs/multer)
- [EJS](https://ejs.co/)
