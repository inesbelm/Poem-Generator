# Poem Generator

This project, born from my personal passion for poetry, is an automated poem generator. It uses advanced natural language processing techniques to create poems, drawing inspiration from various styles and themes.

## Installation

Ensure that Python 3 is installed on your system to run this project.

### Dependencies

To install the necessary libraries, run the following code:
pip install -q kaggle
pip install --upgrade --force-reinstall --no-deps kaggle


### Configuration

1. **Kaggle API Key**: Before downloading the necessary data, configure your Kaggle API key. Download your `kaggle.json` from your Kaggle account and load it into the execution environment with this code:

from google.colab import files
files.upload()


2. **Data Download**: Use the built-in notebook commands to download the poem dataset from Kaggle.

## Usage

Launch the notebook to generate a poem. The system will offer you to choose a style or theme to customize the generated poem.

## Technologies

- Python 3
- Kaggle API
- Natural Language Processing

## Contribution

Suggestions and contributions to improve this project are always welcome. Feel free to submit your ideas or modifications via a pull request.

## License

Distributed under the MIT License, this project is free for everyone to use. See the `LICENSE` file for more details.
