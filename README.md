# PixelPulse 🎨

**PixelPulse** is a modern, web-based painting and image editing application inspired by PaintShop Pro. Built with a fast and lightweight tech stack, it offers a vibrant, user-friendly interface for creating stunning artwork with tools like brushes, shapes, layers, and image filters. Whether you're a hobbyist or a pro, PixelPulse brings creativity to your browser! 🌈

## ✨ Features

- **Real-Time Drawing**: Smooth brush strokes, customizable colors, sizes, and opacity using HTML5 Canvas and Konva.js.
- **Layer Support**: Create, edit, and manage multiple layers for complex compositions.
- **Image Editing**: Apply filters, crop, resize, and export images in PNG/JPEG formats using Sharp.
- **Cloud Storage**: Save and retrieve projects via Cloudinary integration.
- **Responsive UI**: Sleek, mobile-friendly design with Tailwind CSS.
- **Cross-Platform**: Works on desktops, tablets, and mobile devices with touch support.
- **Undo/Redo**: Easily correct mistakes with history tracking.
- **Export Options**: Save your artwork locally or share it online.

## 🚀 Tech Stack

- **Frontend**: React.js, Tailwind CSS, Konva.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Image Processing**: Sharp
- **Cloud Storage**: Cloudinary
- **Build Tool**: Vite

## 📦 Installation

Follow these steps to set up PixelPulse locally:

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or Atlas)
- Cloudinary account (for image storage)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/makalin/pixelpulse.git
   cd pixelpulse
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory and add:
   ```
   MONGODB_URI=your-mongodb-uri
   CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
   CLOUDINARY_API_KEY=your-cloudinary-api-key
   CLOUDINARY_API_SECRET=your-cloudinary-api-secret
   ```

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```

5. Open `http://localhost:5173` in your browser to start creating!

## 🖌️ Usage

1. **Create a New Project**: Click "New Canvas" to start drawing.
2. **Tools**: Select brushes, shapes, or text from the toolbar. Customize color, size, and opacity.
3. **Layers**: Add, reorder, or delete layers via the layer panel.
4. **Save & Export**: Save your project to Cloudinary or export as PNG/JPEG.
5. **Share**: Generate a shareable link for your artwork.

Check out the [Documentation](docs/) for detailed guides and tutorials.

## 🤝 Contributing

We love contributions! Here's how you can help:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/awesome-feature`).
3. Make your changes and commit (`git commit -m 'Add awesome feature'`).
4. Push to the branch (`git push origin feature/awesome-feature`).
5. Open a pull request.

Please read our [Contribution Guidelines](CONTRIBUTING.md) and adhere to the [Code of Conduct](CODE_OF_CONDUCT.md).

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

## 🙌 Acknowledgments

- [Konva.js](https://konvajs.org/) for awesome canvas functionality.
- [Tailwind CSS](https://tailwindcss.com/) for styling magic.
- [Cloudinary](https://cloudinary.com/) for image storage.
- [Sharp](https://sharp.pixelplumbing.com/) for image processing.

## 📬 Contact

Have questions? Reach out via [GitHub Issues](https://github.com/your-username/pixelpulse/issues) or connect with us on [X](https://x.com/your-username).

---

⭐ **Star this project if you find it inspiring!** Let's make the web a more colorful place! 🌈
