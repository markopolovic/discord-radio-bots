# Radio Bots

## Overview

Ionia Radio is a collection of Discord bots that stream various radio stations into designated voice channels. These bots operate independently and provide 24/7 music streaming to users.

## Features

- 🎵 Streams different radio stations (NTS, Lofi, Jazz, Techno, etc.)
- 🤖 Each bot operates in its own voice channel
- 🔄 Auto-reconnect to voice channels if disconnected
- 🛠 Hosted on Google Cloud for continuous uptime

## Installation & Setup

### 1. Clone the Repository

```sh
git clone https://github.com/markopolovic/ionia-radio-bots.git
cd ionia-radio-bots
```

### 2. Install Dependencies

```sh
pip install -r requirements.txt
```

### 3. Set Up Environment Variables

Create a `.env` file and add your bot tokens:

```
BOT_TOKEN_NTS1=your_token_here
BOT_TOKEN_NTS2=your_token_here
BOT_TOKEN_LOFI=your_token_here
BOT_TOKEN_JAZZ=your_token_here
BOT_TOKEN_TECHNO=your_token_here
```

### 4. Run the Bots

```sh
python3 ionia_radio.py
```

## Deployment on Google Cloud

1. Create a VM instance in Google Cloud Compute Engine.
2. Set up Python and install dependencies.
3. Upload your bot scripts to the VM.
4. Run the bots in a `tmux` session for persistent uptime.

## Contributing

Feel free to fork this repository and submit pull requests!

## Contact

GitHub: markopolovic

