https://jan.ai/

# Jan AI Response Streamer

A sleek and intuitive desktop application that provides a seamless interface for interacting with Jan AI.

This app features real-time response streaming, allowing you to see AI responses as they're being generated, with support for markdown formatting for beautifully styled outputs.

Built with Python and Tkinter, it offers essential features like adjustable temperature settings, customizable system prompts, and the ability to stop generation mid-stream.

Perfect for developers and users who want a native, lightweight interface for their local Jan AI instance.

## Features

- Clean and modern Tkinter-based GUI interface
- Real-time response streaming from Jan AI
- Markdown rendering support
- Stop generation functionality
- Environment variable configuration
- System-like theme with custom styling

## Prerequisites

- Python 3.x
- Jan AI running locally

## Installation

1. Clone this repository:
```bash
git clone [repository-url]
cd [repository-name]
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your environment variables:
   - Copy `.env-example` to `.env`
   - Update the variables in `.env` with your configuration

## Dependencies

- requests==2.31.0
- markdown==3.5.2
- python-dotenv==1.0.1

## Usage

1. Ensure Jan AI is running locally on your machine
2. Run the application:
```bash
python main.py
```

3. Use the interface to:
   - Enter your prompts
   - View real-time responses
   - Stop generation when needed
   - View formatted markdown output

## Environment Variables

Create a `.env` file with the following variables (see `.env-example`):
- `JAN_API_URL`: The URL of your Jan AI instance
- Other configuration variables as needed

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add your license information here] 