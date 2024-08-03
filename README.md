# Open Command Window Here as Administrator

This repository provides registry files to add "Open command window here as administrator" and "Open command window here" options to the context menu in Windows 10. This makes it easier to open a command prompt directly in the directory you're currently browsing.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Uninstallation](#uninstallation)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Prerequisites

- Windows 10
- Administrative privileges

### Steps

1. **Download the repository:**

    ```sh
    git clone https://github.com/9M2PJU/Windows-CMD-Context-Menu.git
    cd Windows-CMD-Context-Menu
    ```

2. **Install the registry files:**

    - **Open command window here as administrator:**
    
        Double-click on `OpenCommandWindowHereAsAdmin.reg` and confirm the changes to your registry.
    
    - **Open command window here:**
    
        Double-click on `OpenCommandWindowHere.reg` and confirm the changes to your registry.

## Usage

### Open Command Window Here as Administrator

1. Right-click on any folder or within any directory.
2. Select "Open command window here as administrator" from the context menu.
3. A command prompt will open with administrative privileges in the selected directory.

### Open Command Window Here

1. Right-click on any folder or within any directory.
2. Select "Open command window here" from the context menu.
3. A command prompt will open in the selected directory.

## Uninstallation

To remove the context menu options, you can use the `Uninstall_OpenCommandWindowHereAsAdmin.reg` and `Uninstall_OpenCommandWindowHere.reg` files provided in this repository.

1. **Download the repository (if not already done):**

    ```sh
    git clone https://github.com/9M2PJU/Windows-CMD-Context-Menu.git
    cd OpenCommandWindowHere
    ```

2. **Uninstall the registry files:**

    - **Open command window here as administrator:**
    
        Double-click on `Uninstall_OpenCommandWindowHereAsAdmin.reg` and confirm the changes to your registry.
    
    - **Open command window here:**
    
        Double-click on `Uninstall_OpenCommandWindowHere.reg` and confirm the changes to your registry.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
