# P2P File Sharing System

This Python project implements a peer-to-peer (P2P) file-sharing system using socket programming. The system allows users to host and download files over a local network.

## Features

- Efficient P2P file transfer using both TCP and UDP sockets.
- Smart file handling with binary operations and chunking for optimized large file transfers.
- Concurrent processing to enhance system performance, enabling simultaneous operations for incoming connections and file serving.
- Robust security measures with firewall configurations and error handling for increased reliability.
- Modular project architecture, featuring separate scripts for hosting, downloading, and service announcement for collaborative development.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/P2P-File-Sharing.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Peer2Peer-File_Sharing_System
   ```
3. Run the script to announce the information:

   ```bash
   python announcer.py
   ```
4. Run the script to listen to the information:

   ```bash
   python listener.py
   ```
5. Run the server script:

   ```bash
   python server.py
   ```

5. Run the client script:

   ```bash
   python downloader.py
   ```

## Configuration

- Customize the project settings in the scripts, such as port numbers, file paths, and network configurations.
- Ensure that firewall rules are configured to allow communication on the specified ports.

## Dependencies

- Python 3.x

## Contributing

Contributions are welcome! If you have ideas for improvements or encounter issues, feel free to open an issue or submit a pull request.


Make sure to replace placeholders like `your-username` and add relevant details such as project dependencies, additional configuration steps, or specific usage instructions based on your project's characteristics.
