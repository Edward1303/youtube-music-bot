# 🎶 YouTube Music Bot

![GitHub stars](https://img.shields.io/github/stars/Edward1303/youtube-music-bot?style=social) ![GitHub forks](https://img.shields.io/github/forks/Edward1303/youtube-music-bot?style=social) ![GitHub issues](https://img.shields.io/github/issues/Edward1303/youtube-music-bot?style=social)

## Description

YouTube Music Bot is a ready-to-deploy Telegram bot that allows users to download audio from YouTube. Built with Python and utilizing popular libraries, this bot provides a simple and effective way to enjoy music from your favorite videos.

## Features

- **Download Audio**: Easily download audio tracks from YouTube videos.
- **User-Friendly**: Simple commands make it easy for anyone to use.
- **Multi-Platform**: Works seamlessly across different devices.
- **Efficient**: Built using Celery for background tasks, ensuring smooth performance.
- **Containerized**: Use Docker for easy deployment and scaling.

## Topics

This project utilizes several technologies and frameworks:

- **aiogram**: For building the Telegram bot.
- **Celery**: For handling background tasks.
- **Docker**: For containerization.
- **Docker Compose**: For managing multi-container applications.
- **Flower**: For monitoring Celery tasks.
- **MySQL**: For database management.
- **Redis**: For caching and message brokering.
- **Python**: The primary programming language.
- **Telegram**: The messaging platform.

## Getting Started

To get started with the YouTube Music Bot, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- Docker
- Docker Compose

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Edward1303/youtube-music-bot.git
   cd youtube-music-bot
   ```

2. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add your Telegram bot token and other necessary configurations.

3. **Build the Docker Containers**:
   ```bash
   docker-compose build
   ```

4. **Run the Application**:
   ```bash
   docker-compose up
   ```

5. **Access the Bot**:
   Find your bot on Telegram and start using it!

### Download the Latest Release

To get the latest version of the bot, visit the [Releases](https://github.com/Edward1303/youtube-music-bot/releases) section. Download the latest release and execute it as per the instructions.

## Usage

Once the bot is running, you can use the following commands:

- `/start`: Start the bot and get a welcome message.
- `/download <YouTube URL>`: Download audio from the provided YouTube link.

## Example Commands

1. **Starting the Bot**:
   Simply type `/start` in your Telegram chat with the bot.

2. **Downloading Music**:
   To download a track, send the command:
   ```
   /download https://www.youtube.com/watch?v=example
   ```

   The bot will process your request and send you the audio file.

## Configuration

You can customize the bot's behavior by modifying the configuration settings in the `.env` file. Here are some key variables you might want to set:

- `TELEGRAM_TOKEN`: Your bot's token from the BotFather.
- `MYSQL_HOST`: Hostname for your MySQL database.
- `REDIS_URL`: URL for your Redis instance.

## Monitoring

You can monitor your Celery tasks using Flower. To do this, run the following command in a separate terminal:

```bash
docker-compose up flower
```

Access Flower by navigating to `http://localhost:5555` in your web browser.

## Contributing

We welcome contributions! If you'd like to contribute to the YouTube Music Bot, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [aiogram](https://github.com/aiogram/aiogram): The framework that powers the bot.
- [Celery](https://docs.celeryproject.org/en/stable/): For background task management.
- [Docker](https://www.docker.com/): For containerization.
- [Redis](https://redis.io/): For caching and message brokering.
- [MySQL](https://www.mysql.com/): For database management.

## Contact

For any questions or support, feel free to open an issue in the repository or contact me directly.

## Download the Latest Release Again

To download the latest release again, you can visit the [Releases](https://github.com/Edward1303/youtube-music-bot/releases) section. Make sure to follow the instructions for execution after downloading.

---

Feel free to explore the code and make improvements. Enjoy your music! 🎧