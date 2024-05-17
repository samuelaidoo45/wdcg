# AI Content Generator

## Overview

The AI Content Generator is a web application designed to assist users in generating high-quality Word documents quickly and easily. It allows users to input a document title, context, and sections, and then generates the document content using AI. The application also provides a preview of the document and includes a pop-up for user engagement.

## Features

- **Document Title Input**: Users can input the title of the document.
- **Context Input**: Users can provide the context or main issue the document addresses.
- **Section Input**: Users can add multiple sections to the document.
- **Document Preview**: The application provides a preview of the document with title, context, and sections.
- **Edit and Delete Sections**: Users can edit or delete sections before generating the document.
- **Generate Content**: Users can generate the document content and download it as a Word file.
- **User Engagement Pop-up**: A pop-up is displayed to welcome users and provide additional information.
- **Responsive Design**: The application is responsive and works well on both mobile and desktop devices.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- SweetAlert2 for alerts and pop-ups
- docx.js for generating Word documents
- Firebase for analytics
- Showdown.js for markdown to HTML conversion

## Project Structure

```
.
├── index.html        # Main HTML file
├── spin.css          # CSS for loading spinner
├── README.md         # Project README file
└── assets/           # Directory for additional assets (images, etc.)
```

## Getting Started

### Prerequisites

To run this project, you need to have a modern web browser and an internet connection.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/ai-content-generator.git
   cd ai-content-generator
   ```

2. **Open the `index.html` file in your browser**.

## Usage

1. **Open the application** in your web browser using the link https://samuelaidoo45.github.io/wdcg/.
2. **Enter the document title** in the title input field.
3. **Provide the context** for the document in the context input field.
4. **Add sections** by typing the section content in the section input field and clicking the "Add Section" button.
5. **Preview the document** in the preview section.
6. **Edit or delete sections** using the respective buttons in the preview section.
7. **Generate the document** by clicking the "Generate Content" button.
8. **Download the document** as a Word file.

## Firebase Configuration

The application uses Firebase for analytics. The Firebase configuration is included in the HTML file. To use Firebase analytics, replace the Firebase configuration with your own:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
```

## Contributing

1. **Fork the repository**.
2. **Create a new branch** for your feature or bugfix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit your changes**:
   ```bash
   git commit -m "Add some feature"
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a pull request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For feedback or questions, please contact Sam Aidoo at [samuelaidoo45@gmail.com](mailto:samuelaidoo45@gmail.com). Follow on [Twitter](https://twitter.com/_samuelaidoo).

---

Thank you for using the AI Content Generator!