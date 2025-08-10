# AI-Image-Enhancer

An interactive React-based web app that leverages the **PicWish API** to enhance image quality, upscale resolution, and improve visual details—delivering real-time before-and-after previews with effortless AI-powered processing.

##  Features

- **AI Image Enhancement**: Seamlessly enhance image clarity, sharpness, and resolution using the PicWish API.
- **Real-Time Previews**: Instantly compare the original and enhanced images side-by-side.
- **User-Friendly UI**: Built with React, featuring responsive design and smooth interactions.
- **Simple Workflow**: Upload an image, trigger enhancement, and receive the improved result.

##  Getting Started

###  Prerequisites

- Node.js & npm (v14+ recommended) installed on your machine.
- A valid **PicWish API key** (obtainable from PicWish documentation or developer portal).

###  Installation

```bash
# Clone the repository
git clone https://github.com/tanyatanwer12/AI-image-enhancer.git
cd AI-image-enhancer

# Install dependencies
npm install
````

### Configuration

Create a `.env` file in the project root and add:

```env
REACT_APP_PICWISH_API_KEY=your_picwish_api_key_here
```

Ensure you're referencing this environment variable securely in your code.

### Running the App

```bash
npm start
```

The app will run at [http://localhost:3000](http://localhost:3000). Upload an image to see AI enhancements in action.

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` directory.

## Project Structure

* `public/` — Static assets and HTML template.
* `src/` — Main React source code.

  * `components/` — UI components (upload button, preview panels, etc.).
  * `utils/` — API interaction logic and helpers (e.g., PicWish integration).
* Configuration files: `package.json`, `tailwind.config.js`, `postcss.config.js`.

## Technologies Used

* **React** (via Create React App) — Frontend UI framework.
* **PicWish API** — AI-powered image enhancement backend.
* **Tailwind CSS** — Utility-first styling framework.
* Environment Setup — `.env` for secure API key access.

## Usage Workflow

1. Upload an image using the file input.
2. The PicWish API processes the image and returns an enhanced version.
3. The app displays both original and enhanced images side-by-side for easy comparison.

## Contributing

You’re welcome to contribute! To do so:

1. Fork the repo.
2. Create a feature branch (`git checkout -b feature-name`).
3. Make your improvements and commit.
4. Push to your branch (`git push origin feature-name`).
5. Submit a Pull Request. Feedback is appreciated!

