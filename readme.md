# Text-to-Speech ML Project: Convert ePub Books to Audiobooks

![1681477053391](image/readme/1681477053391.png)

This is a machine learning project that utilizes the `ebook-convert` tool provided by Calibre, along with the Tortoise API, to convert ePub books to text and then generate audiobooks. The project is implemented using Jupyter Notebook on Google Colab, and it allows users to choose and upload their preferred voice for the audiobook.

## Features

* Convert ePub books to text: The project leverages the `ebook-convert` tool from Calibre to extract the text content from ePub books, making it available for further processing.
* Generate Audiobooks: The Tortoise API is used to convert the extracted text into an audiobook, providing users with an audible version of the book that can be listened to on the go.
* Voice Selection: Users have the option to pick/upload their desired voice for the audiobook, allowing for customization and personalization of the listening experience.
* Google Colab Compatibility: The project is implemented in Jupyter Notebook using Google Colab, providing a convenient and accessible platform for running the code and experimenting with different settings.

## Dependencies

* Calibre: The `ebook-convert` tool is used to convert ePub books to text. Please make sure to have Calibre installed on your system.
* Tortoise API: This is a Python library that provides text-to-speech capabilities for generating audiobooks. It can be installed via pip using the following command: `!pip install tortoise-voice`.
* Google Colab: The project is designed to be run on Google Colab, so make sure you have a Google account and access to a Colab environment.

## Usage

1. Install the necessary dependencies, including Calibre and Tortoise API, as mentioned in the Dependencies section.
2. Upload the ePub book that you want to convert to an audiobook to your Google Colab environment.
3. Open the Jupyter Notebook file provided in this repository on Google Colab.
4. Follow the instructions in the Jupyter Notebook to run the code cells and execute the text-to-speech ML project.
5. Customize the settings as desired, such as choosing the voice for the audiobook.
6. Once the code has been executed, the generated audiobook will be available for download or playback, depending on the options chosen.
7. Enjoy listening to the audiobook version of your ePub book on the go!

## Acknowledgments

This project makes use of the following tools and libraries:

* Calibre: An open-source e-book management tool that provides the `ebook-convert` tool for converting ePub books to text.
* Tortoise API: A Python library that provides text-to-speech capabilities for generating audiobooks.
* Google Colab: A cloud-based Jupyter Notebook environment provided by Google for running and sharing code in the form of notebooks.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE), which allows for free use, modification, and distribution, but comes with no warranties or guarantees. Please review the license file for more information.

## Conclusion

Thank you for considering and using our Text-to-Speech ML Project for converting ePub books to audiobooks. We hope this project provides a convenient and accessible way for you to enjoy your favorite books in an audible format. If you have any questions, feedback, or suggestions, please feel free to contact us or submit an issue on GitHub. Happy listening
