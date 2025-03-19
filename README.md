# AniWatch - Ad-Free Anime Watcher

AniWatch is a simple ad-free anime-watching terminal application for **Ubuntu Linux**, built using **MPV** and **Ani-CLI**. This allows you to watch your favorite anime without distractions, directly from your terminal.

## Features
- **Ad-free** experience
- **Lightweight** and terminal-based
- **Seamless playback** using MPV
- **Search and stream anime easily** using Ani-CLI

## Prerequisites
Before you begin, make sure you have the following installed:

1. **MPV** - A powerful media player
   ```bash
   sudo apt update && sudo apt install mpv -y
   ```
2. **Ani-CLI** - A command-line anime streaming tool
   ```bash
   git clone https://github.com/pystardust/ani-cli.git
   cd ani-cli
   sudo make install
   ```

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/aniwatch.git
   cd aniwatch
   ```
2. Give execute permission to the script:
   ```bash
   chmod +x aniwatch.sh
   ```
3. Run the script:
   ```bash
   ./aniwatch.sh
   ```

## Usage
- Search for an anime using Ani-CLI:
  ```bash
  ani-cli -s "Anime Name"
  ```
- Select an episode and enjoy ad-free streaming with MPV.

## Example
```bash
ani-cli -s "One Piece"
```
_Select the episode and it will play via MPV._

## Contributing
Feel free to fork the repository, submit issues, or create pull requests.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## Author
Developed by **Harsh Arora**.
