# AI Image Generator

## Short Description

This project is a simple AI-powered text-to-image generator built using HTML, CSS, and JavaScript. It allows users to input a text prompt and generate an image based on that prompt using the OpenAI API.  The entire application is contained within a single `index.html` file for ease of deployment and understanding.

## Features

*   **Text-to-Image Generation:** Takes a text prompt as input and generates an image.
*   **OpenAI Integration:** Uses the OpenAI API (DALL-E) to generate images.
*   **Simple User Interface:**  A clean and intuitive user interface for entering prompts and viewing generated images.
*   **Loading Indicator:** Shows a loading animation while the image is being generated.
*   **Error Handling:** Displays an error message if the image generation fails.
*   **All-in-one file:** The whole application is contained in a single index.html file

## Requirements

*   **OpenAI API Key:**  You need an OpenAI API key to use this application. You can obtain one from the [OpenAI website](https://platform.openai.com/).
*   **Web Browser:** A modern web browser (Chrome, Firefox, Safari, Edge) is required to run the application.
*   **Internet Connection:** An internet connection is required to access the OpenAI API.

## Installation

Since the application consists of a single HTML file, installation is very straightforward:

1.  **Download the `index.html` file:** Download or clone the `img_generator/img.html` file from the repository.
2.  **Rename the `img.html` file:** Rename the file to `index.html`.
3.  **Open the file:** Open the `index.html` file in your web browser.

## Usage

1.  **Open `index.html` in your browser.**
2.  **Enter your OpenAI API key:** Modify the `index.html` file as explained in the Configuration section to include your OpenAI API key.
3.  **Enter a text prompt:** Type a description of the image you want to generate into the input field.
4.  **Click the "Generate Image" button:** This will send the prompt to the OpenAI API and generate an image.
5.  **View the generated image:** The generated image will be displayed below the input field.  A loading animation will be shown while the image is being generated.  An error message will be displayed if something goes wrong.

## File Structure

```
img_generator/
└── index.html       # Contains all the HTML, CSS, and JavaScript code.
```

## Testing

This project does not include automated tests. To test the application, you can:

1.  Open the `index.html` file in your browser.
2.  Enter a variety of text prompts and verify that the generated images are appropriate.
3.  Test error handling by intentionally using an invalid OpenAI API key or by disconnecting from the internet.

## Configuration

The only required configuration is your OpenAI API key.  You must insert your API key directly into the JavaScript code within `index.html`.

1.  **Open `index.html` in a text editor.**
2.  **Find the JavaScript code:** Look for the line containing `const apiKey = 'YOUR_API_KEY';`
3.  **Replace `YOUR_API_KEY` with your actual OpenAI API key.**  For example: `const apiKey = 'sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx';`
4.  **Save the file.**

**Important:** Be careful not to commit your API key to a public repository.  Consider using environment variables or a more secure method for storing your API key if you plan to share or deploy this application.

## Contributing

Contributions are welcome! To contribute to this project, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your forked repository.
5.  Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Improvements

Here are some potential improvements for this project:

*   **Error Handling:** Improve error handling to provide more informative error messages to the user.
*   **API Key Security:** Implement a more secure method for storing the OpenAI API key (e.g., environment variables, backend proxy).
*   **Image Quality and Size:** Add options to control the image quality and size.
*   **UI Enhancements:** Improve the user interface with features like image download, history, and more advanced prompt options.
*   **Automated Testing:** Add automated tests to ensure the application is working correctly.
*   **Deployment:** Containerize the application to allow for simpler deployment.
*   **More robust CSS styling:** Improve the visual appearance of the application.
*   **Responsiveness:** Improve the layout to be more responsive to various device sizes
*   **Use external JavaScript:** Move the Javascript code to an external file.
