# rmsh (Remote Shell)

**rmsh** is a remote shell application that allows you to execute commands on a remote server. It features a server and client architecture for easy management and command execution.

## Features

- Remote command execution on a server
- User authentication with configurable permissions
- Command logging for auditing
- File upload and download functionality
- Flask-based web admin panel for user management and logs
- Customizable command aliases and session timeouts

## Installation

### Prerequisites

Make sure you have Python 3 and Flask installed on your system. You can install Flask with the following command:

```bash
pip install flask
```
### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rmsh.git
   cd rmsh
   ```
2. Run the installer script for the server:
   ```bash
   bash installer_server.sh
   ```
3. Run the installer script for the client:
   ```bash
   bash installer_client.sh
   ```
## Usage

### Starting the Server

After installation, you can start the server using:

```bash
python server.py
```

### Running the Client

To connect to the server, run:

```bash
python client.py
```

You will be prompted for your username and password.

### Admin Panel

Access the web-based admin panel by navigating to `http://yourdomain:8081` in your web browser. Here you can manage users and view command logs.

## Configuration

Configuration files will be stored in `~/.rmsh/config/`. You can edit `uac.conf` to manage user accounts and permissions.

## Contributing

Feel free to contribute to this project! Open issues or submit pull requests to improve functionality.

## License

This project is licensed under the MIT License.
