# Conda env set up
Init & set up a conda enviroment.

## Table of Contents:

- [Prerequisites](#prerequisites)
- [Setting virtual enviroment](#setting-virtual-enviroment)
  - [create](#create)
  - [activate](#activate)
  - [install](#install)
- [Download Libraries](#downlowad-libraries)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Install anaconda: https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html

## Setting virtual enviroment

How to set up and run the project locally.

### Create
1. Change 'test-env' :

```bash
conda deactivate
conda create --name test-env
```

### Activate

2. Activate the enviroment previously created:

```bash
    conda activate test-env
```
    
### Install

3. Install desired version of python

    ```bash
    conda install Python=3.9
    ```
    
## Download Libraries

Download the necessary libraries
```bash
conda install pyautogui, numpy, PIL
```
Update (optional)
```bash
conda update
```

## Summary

To summarize we may start a conda enviroment and set it up using th elines below:

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
