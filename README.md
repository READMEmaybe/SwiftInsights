# Renamer-CLI

Renamer-CLI is a simple command-line tool designed to streamline file management tasks, particularly for data scientists and developers. With customizable naming patterns and intuitive features, Renamer-CLI empowers users to effortlessly organize and rename files, saving time and enhancing productivity across various projects and workflows.

## Table of Contents

- [The Story](#the-story)
- [Installation](#installation)
- [Usage](#usage)
- [Patterns](#patterns)
  - [Name and Extension](#name-and-extension)
  - [Parent Directory](#parent-directory)
  - [Date](#date)
  - [More Soon...](#more-soon)
- [Options](#options)
  - [File Only](#file-only)
  - [Directory Only](#directory-only)
  - [Extension](#extension)
  - [Interactive](#interactive)
  - [Recursive](#recursive)
  - [Undo](#undo)
- [Contrubuting](#contrubuting)
- [License](#license)


## The Story

As an aspiring developer with a keen interest in data science, I often find myself diving into various projects and datasets to hone my skills and explore different aspects of data analysis. However, I encountered a common frustration that many aspiring data scientists face: the chaos of file management. With each new dataset I acquired and project I embarked upon, I found myself grappling with the cumbersome task of organizing and renaming files, each with its own cryptic naming conventions and jumbled formats.

Driven by my passion for data and determination to streamline my workflow, I embarked on a quest to develop a solution that would alleviate the pains of file management and empower data scientists like myself to focus more on the exciting aspects of data analysis. Thus, Renamer-CLI was born—an evolving command-line tool crafted to tackle the challenges of file renaming and organization.

As I immersed myself in the development process, Renamer CLI quickly became an indispensable asset in my toolkit. Its customizable naming patterns, such as {name}, {date}, and {ext}, empowered me to generate clear and consistent filenames tailored to each project's needs, saving me countless hours of manual labor.

While Renamer-CLI is still in its early stages of development, its impact on my workflow has been profound. Despite being a relatively new project, it has already saved me a significant amount of time and effort in managing my files. The ability to quickly and efficiently rename and organize files using customizable patterns has allowed me to maintain a sense of order amidst the chaos of data exploration and analysis.

Moreover, the process of developing Renamer-CLI has been a journey of discovery and learning. Through each line of code written and each feature implemented, I have gained valuable insights into software development practices, command-line tools, and the nuances of file management. Each challenge encountered along the way has been an opportunity for growth, and I am continuously refining and improving Renamer-CLI to better serve the needs of data scientists and enthusiasts alike.

Though the road ahead may be long and the journey of perfecting Renamer-CLI is ongoing, I am excited by the possibilities it holds. With each iteration, I am one step closer to realizing its full potential and providing a valuable resource for the data science community. As I continue to learn and evolve as a developer, I am committed to enhancing Renamer-CLI and empowering others to conquer the challenges of file management in their data science endeavors.

## Installation

Renamer-CLI requires Python 3 and pip to be installed on your system. You can install Renamer-CLI using pip:

```bash
pip install renamer-cli
```

## Usage

Renamer-CLI offers a variety of powerful features to streamline your file management tasks.

```bash
usage: renamer [-h] [-d DIRECTORY] [-p PATTERN] [-f] [-D] [-e EXTENSIONS [EXTENSIONS ...]] [-r] [-i] [-u]

Rename files and directories based on a user-defined pattern

options:
  -h, --help            show this help message and exit
  -d DIRECTORY, --directory DIRECTORY
                        Path to the directory containing files and directories to be renamed.
  -p PATTERN, --pattern PATTERN
                        Naming pattern for renaming files and directories. Use placeholders like {name}, {parent}, {date}, etc.
  -f, --files-only      Rename only files, not directories.
  -D, --directories-only
                        Rename only directories, not files.
  -e EXTENSIONS [EXTENSIONS ...], --extensions EXTENSIONS [EXTENSIONS ...]
                        Rename only files with specified extensions.
  -r, --recursive       Perform renaming recursively, including files and directories in subdirectories.
  -i, --interactive     Enable interactive mode for manual confirmation of each renaming operation.
  -u, --undo            Undo the last file and directory renaming operation.
```

## Patterns
### Name and Extension
Renamer-CLI allows you to customize filenames by incorporating both name and extension.

![name pattern](https://vhs.charm.sh/vhs-676KFAPndNosYsiLl08LCx.gif)
### Parent Directory
Easily include the parent directory name in your filenames for better organization.

![Parent dir pattern](https://vhs.charm.sh/vhs-4AftDGmSpPmgG6lORmjZpC.gif)
### Date
Automatically add date information to your filenames for versioning or sorting.

![Date pattern](https://vhs.charm.sh/vhs-qTd4h572QERwN3p40jvkA.gif)
### More Soon...
Stay tuned for additional pattern options coming soon!

## Options
All these options can be combined to tailor the renaming process to your specific needs.
### File Only
Effortlessly filter and rename files only, leaving directories untouched.

![file only](https://vhs.charm.sh/vhs-5Z4qERUhcpkwNnVST69jbX.gif)
### Directory Only
Similarly, focus exclusively on directories, perfect for organizing your file structure.

![Directory only](https://vhs.charm.sh/vhs-4eiqzUYTf0WM9ywJCEG1Cy.gif)
### Extension
Refine your renaming process by filtering files based on specific extensions.

![By Extension](https://vhs.charm.sh/vhs-1sxy0n14iZ5JqZ1YmTE8Vm.gif)
### Interactive
Engage with an interactive mode to confirm each renaming operation.

![Interactive](https://vhs.charm.sh/vhs-5bPRwcmAeAIzqFWxfgSESf.gif)
### Recursive
Enable recursive mode to apply renaming operations to all subdirectories.

![Recursive](https://vhs.charm.sh/vhs-4fSMdws4HLBvGhAWIq3Qh0.gif)
### Undo
Effortlessly revert the last renaming operation with the undo feature.

![Undo option](https://vhs.charm.sh/vhs-4ngOm4nTPNHrdjOC8tKPjR.gif)


## Contributing

Thank you for considering contributing to renamer-cli! Contributions are welcome from everyone.

### How to Contribute

If you'd like to contribute to renamer-cli, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them to your branch.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

### Code Style

Please adhere to the project's code style and conventions.

### Reporting Issues

If you encounter any issues or have suggestions for improvements, please open an issue on the GitHub repository.

### Contact

If you have any questions or need further assistance, feel free to reach out via GitHub issues.

### License

This project is licensed under the [MIT License](LICENSE).