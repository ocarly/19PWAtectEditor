# Text Editor Application

This project is a text editor application that runs in the browser. It is a single-page application that meets the Progressive Web App (PWA) criteria. The application is designed to function offline and uses a variety of data persistence techniques to ensure redundancy in case one of the options is not supported by the browser.

## Features

- **Single Page Application**: The application is built as a single page application, providing a seamless user experience.
- **Progressive Web App (PWA)**: The application meets the PWA criteria, ensuring it can be installed on your device and used offline.
- **Data Persistence**: The application uses a variety of data persistence techniques to ensure data is not lost even if one of the options is not supported by the browser.
- **Offline Functionality**: The application is designed to function offline, providing users with the ability to continue editing their documents without an internet connection.

## Technologies Used

- **IndexedDB**: The application uses IndexedDB for data storage. IndexedDB is a low-level API for client-side storage of significant amounts of structured data, including files/blobs.
- **IDB**: The application uses the IDB package, a lightweight wrapper around the IndexedDB API. It provides a number of methods that are useful for storing and retrieving data.

## Getting Started

To get started with this project, clone the repository and install the necessary dependencies.

```bash
git clone https://github.com/yourusername/text-editor.git
cd text-editor
npm install
```

Then, start the development server:

```bash
npm run start
```

Now, you can open your browser and navigate to `http://localhost:3000` to see the application in action.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the terms of the MIT license.