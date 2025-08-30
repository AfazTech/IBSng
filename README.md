# IBSNG Radius Server

## Overview

**IBSNG** is a robust Radius Server that provides comprehensive support for various devices. Optimized for ease of installation and configuration, this free software is designed for CentOS 7 systems. The installation process has been streamlined with the creation of the `install.sh` script, ensuring a straightforward setup experience for users with root privileges.

## Integrated Installation Guide

### Prerequisites

- **Operating System:** CentOS 7
- **User Privileges:** Root access is required for installation.

### Quick Setup Steps

Follow these steps to swiftly install and configure the IBSNG Radius Server on your CentOS 7 system using the `install.sh` script:

1. **Run the Command**

    ```bash
    bash <(curl -s https://raw.githubusercontent.com/AfazTech/IBSng/main/install.sh)
    ```

2. **Follow On-Screen Instructions**

    The script will seamlessly guide you through essential tasks such as package installation, PostgreSQL database initialization, repository cloning, firewall setup, and more.

### Post-Installation Checklist

- **Access Your IBSNG Server**

    Visit http://server-ip/IBSng/admin to log in:
    
    - **Username:** system
    - **Password:** system

- **Security Suggestions**

    Change the default password and secure the admin panel by restricting IP access promptly.

  
### [training ibsng (persion)](https://raw.githubusercontent.com/imafaz/IBSng/main/training.pdf)


## Further Customization

Congratulations! You have successfully installed the IBSNG Radius Server using the `install.sh` script. For additional customization and configuration options, consult the official documentation or explore the repository.

## License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for more information.
