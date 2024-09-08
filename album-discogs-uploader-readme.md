# Album Discogs Uploader

This Node.js application uses OpenAI's GPT-4 Vision model to analyze album cover images and automatically generate and upload entries to Discogs.

## Features

- Image analysis using OpenAI's GPT-4 Vision model
- Automatic generation of Discogs entries based on AI analysis
- Integration with Discogs API for uploading entries

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v14.0.0 or later)
- npm (usually comes with Node.js)
- An OpenAI API key with access to GPT-4 Vision
- A Discogs account and API credentials

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/album-discogs-uploader.git
   cd album-discogs-uploader
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```
   OPENAI_API_KEY=your_openai_api_key
   DISCOGS_CONSUMER_KEY=your_discogs_consumer_key
   DISCOGS_CONSUMER_SECRET=your_discogs_consumer_secret
   ```

## Usage

1. Place your album cover image in the project directory.

2. Update the `imagePath` in the `main` function of `index.js` to point to your image file.

3. Run the script:
   ```
   node index.js
   ```

4. The script will analyze the image, generate a Discogs entry, and attempt to upload it to your Discogs account.

## Contributing

Contributions to the Album Discogs Uploader are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [@your_twitter](https://twitter.com/your_twitter) - email@example.com

Project Link: [https://github.com/yourusername/album-discogs-uploader](https://github.com/yourusername/album-discogs-uploader)

## Acknowledgements

- [OpenAI](https://openai.com/)
- [Discogs API](https://www.discogs.com/developers/)
- [Node.js](https://nodejs.org/)
