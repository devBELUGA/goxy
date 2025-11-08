# Goxy - The Open-Source Telegram Bot

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Rust Edition](https://img.shields.io/badge/rust%20edition-2025-orange.svg?logo=rust)](https://www.rust-lang.org/)
[![Project Status](https://img.shields.io/badge/status-active-brightgreen.svg)](https://github.com/devBELUGA/goxy/)
[![GitHub stars](https://img.shields.io/github/stars/devBELUGA/goxy.svg?style=social)](https://github.com/devBELUGA/goxy/stargazers)

A modular and high-performance Telegram bot built with Rust, designed to be powerful, extensible, and easy to maintain.

Version: v0.1  
Language: Rust 🦀

## ✨ Key Features

*   **⚡ Blazing Fast:** Engineered with Rust for optimal performance and near-instantaneous response times.
*   **🔒 Secure & Reliable:** Leveraging Rust's memory safety to build a crash-resistant and secure application.
*   **🧩 Modular Architecture:** Easily extend the bot's functionality with custom plugins and commands.
*   **⚙️ Minimal Dependencies:** A lightweight footprint, keeping the project clean and focused.

## 🛠️ Tech Stack

*   **Language:** [Rust](https://www.rust-lang.org/)
*   **Async Runtime:** [Tokio](https://tokio.rs/)
*   **Telegram API:** [Teloxide](https://github.com/teloxide/teloxide)

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Rust (latest stable version) & Cargo

### Installation & Running

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/devBELUGA/goxy.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd goxy
    ```

3.  **Create the environment file:**
    Create a `.env` file in the root directory and add your Telegram bot token.
    ```ini
    TELEGRAM_BOT_TOKEN="your_super_secret_token_here"
    ```

4.  **Build and run the project:**
    For a development build with live-reloading:
    ```sh
    cargo watch -q -c -x run
    ```
    For a standard development build:
    ```sh
    cargo run
    ```
    For a production-optimized build:
    ```sh
    cargo build --release
    ```

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Feel free to fork the repository, create a feature branch, and open a pull request. You can also open an issue with your suggestions.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
