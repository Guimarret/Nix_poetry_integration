**Poetry in Nix Flakes Template**

This GitHub repository serves as a template for setting up a project that uses Poetry for Python dependency management within the Nix ecosystem using Nix flakes. This documentation provides a guide on how to use this template effectively.

### Features

- **Poetry Integration**: Utilizes Poetry for managing Python dependencies, providing a reliable and consistent environment.
- **Nix Flakes**: Implements Nix flakes for reproducible and declarative package management.
- **Project Structure**: Offers a basic project structure to kickstart your development process.

### Prerequisites

- [Nix](https://nixos.org/guides/install-nix.html) installed on your system.
- [Poetry](https://python-poetry.org/docs/#installation) installed on your system.

### Usage

- **Shell**: To build your project using Nix flakes, you can use the following commands:

  ```bash
  nix develop
  ```
- **Development**: During development, you can use Poetry's commands to manage your dependencies inside the virtual environment. For example:
  
  ```bash
  poetry add <package-name>    # Add a new dependency
  poetry remove <package-name> # Remove a dependency
  ```


### Directory Structure

The directory structure of this template is as follows:

```
.
├── flake.nix            # Nix flake configuration
├── flake.lock           # Lock file for Nix flakes
├── poetry.lock          # Poetry lock file
├── pyproject.toml       # Poetry configuration
└── README.md            # Documentation
```

### Contributing

If you encounter any issues or have suggestions for improvements, feel free to open an issue or pull request on the GitHub repository.

### Acknowledgements

- [Poetry](https://python-poetry.org/)
- [Nix](https://nixos.org/)

---

Feel free to customize this documentation to fit your project's specific needs, also don't forget to change the pyproject.toml authors, names, etc. Happy coding!