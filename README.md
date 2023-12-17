# Conda env set up
Init & set up a conda env.

## Table of Contents:

- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

List any prerequisites that the user needs to have installed before setting up the project.

## Getting Started

Provide instructions on how to set up and run the project locally.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-project.git
    ```
2. Navigate to the project directory:

    ```bash
    cd your-project
    ```
3. Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    ```
4. Activate the virtual environment:

    - For Windows:

        ```bash
        venv\Scripts\activate
        ```

    - For macOS/Linux:

        ```bash
        source venv/bin/activate
        ```
5. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```



## Folder Structure

Ideally it should looc something lik:
project-root/
│
├── src/
│ ├── main.py
│ ├── ...
│
├── tests/
│ ├── test_main.py
│ ├── ...
│
├── requirements.txt
├── README.md
└── .gitignore

## conda project Initialization commands

Welcome to a boilerplate for creating an app using anaconda

## Installation

To run this project, make sure you have Python installed. You can install the required dependencies using:

```bash
conda deactivate
conda create --name test-env
conda activate test-env
conda install pyautogui, Python=3.9
conda update
```

## Contributing

Provide information on how others can contribute to your project.

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
