# Text-to-Speech (TTS) ML Project: Turn EPUB Books into Audiobooks

# Text-to-Speech ML Project: Convert ePub Books to Audiobooks

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

Thank you for considering and using our Text-to-Speech ML Project for converting ePub books to audiobooks. We hope this project provides a convenient and accessible way for you to enjoy your favorite books in an audible format. If you have any questions, feedback, or suggestions, please feel free to contact us or submit an issue on GitHub. Happy listenin

![1681477053391](image/readme/1681477053391.png)

## Text-to-Speech ML Project

This is a machine learning project that utilizes Text-to-Speech (TTS) technology to convert EPUB books into audiobooks. The project is implemented in Jupyter Notebook, and it allows users to input EPUB files, process the text data, and generate audio output in the form of audiobooks. The project utilizes a pre-trained TTS model to generate human-like speech from the text data.

## Features

* Convert EPUB books into audiobooks.
* Utilize a pre-trained TTS model to generate speech.
* Customize audio output settings, such as voice, speed, and volume.
* Process text data, including text normalization, punctuation removal, and sentence segmentation.
* Save generated audiobooks in various audio file formats, such as WAV, MP3, or OGG.
* Visualize the text data and audio output for analysis and evaluation.
* Compatible with popular machine learning libraries such as TensorFlow, PyTorch, and Scikit-learn.

## Requirements

* Python 3.7 or higher
* Jupyter Notebook
* Dependencies: [List the required dependencies and their versions]
* EPUB books for input data

## Installation

1. Clone the repository to your local machine:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/your-username/your-repo.git
</code></div></div></pre>

2. Install the required dependencies:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">pip install -r requirements.txt
</code></div></div></pre>

3. Download and install the pre-trained TTS model:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash"># Provide instructions to download and install the pre-trained TTS model
</code></div></div></pre>

## Usage

1. Open the Jupyter Notebook:

<pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">jupyter notebook
</code></div></div></pre>

2. Navigate to the project directory and open the "Text_to_Speech_ML_Project.ipynb" notebook.
3. Follow the instructions in the notebook to load EPUB books, process the text data, and generate audiobooks using the TTS model.
4. Customize audio output settings, such as voice, speed, and volume, to suit your preferences.
5. Save the generated audiobooks in your desired audio file format.
6. Analyze and evaluate the audio output and text data using the provided visualization tools.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://chat.openai.com/c/LICENSE).

## Acknowledgements

* [List any acknowledgements, credits, or references to external sources that were used in the project]

## Contact

For any questions, comments, or inquiries, please contact [Your Name] at [Your Email Address].
