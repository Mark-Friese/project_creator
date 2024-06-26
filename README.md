
# Project Creator

Project Creator is a tool to automate the creation of project structures, set up virtual environments, and install necessary packages.

## Features

- Supports creation of full stack website, full stack data science, and full stack app projects.
- Automatically sets up virtual environments.
- Installs base requirements and additional specified packages.
- Creates initial project structure with directories and files.

## Installation

You can install the package using pip:

```sh
pip install EZ_project_creator
```

## Usage

Run the tool using the following command:

```sh
project_creator
```

You will be prompted to enter the project location, name, type, and additional packages to install.

### Project Types

- `full_stack_website`: Sets up a Django-based website with front-end components.
- `full_stack_data_science`: Sets up a data science project with directories for raw data, notebooks, and models.
- `full_stack_app`: Sets up a full-stack application, supporting mobile and web components.

## Example

```sh
$ project_creator
Enter the location for the project [/default/path]: /path/to/projects
Enter the project name: my_project
Enter the project type (full_stack_website, full_stack_data_science, full_stack_app): full_stack_website
Enter additional packages to install (comma-separated): requests,beautifulsoup4
```

### Folder Structures

<table>
  <tr>
    <th>Full Stack Website Structure</th>
    <th>Full Stack Data Science Structure</th>
    <th>Full Stack App Structure</th>
  </tr>
  <tr>
    <td><img src="docs/images/full_stack_website.png" alt="Full Stack Website Structure" width="300"></td>
    <td><img src="docs/images/full_stack_data_science.png" alt="Full Stack Data Science Structure" width="300"></td>
    <td><img src="docs/images/full_stack_app.png" alt="Full Stack App Structure" width="300"></td>
  </tr>
</table>

## Configuration

The tool saves the last used project location in a configuration file (`project_config.json`) in the current directory. The next time you run the tool, it will use this location as the default.

## Development

### Setting up for development

1. Clone the repository:

```sh
git clone https://github.com/Mark-Friese/project_creator.git
cd project_creator
```

2. Install the package in editable mode:

```sh
pip install -e EZ_project_creator
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, please open an issue or contact the author at mark.friese.meng@gmail.com
