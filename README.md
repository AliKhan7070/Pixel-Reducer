# Pixel-Reducer

## 🎨 Overview

Pixel-Reducer is a web-based application that compresses images using **K-means clustering**. It reduces the number of unique colors in an image, optimizing file size while preserving essential details. This tool is useful for web developers, designers, and anyone looking to optimize images for performance.

## 🚀 Features

- **Image Upload**: Supports JPG, JPEG, and PNG formats.
- **Color Reduction**: Uses K-means clustering to reduce the number of colors.
- **Image Resizing**: Allows users to specify custom dimensions.
- **Compression Efficiency**: Shows the size reduction percentage.
- **Side-by-Side Comparison**: Displays original and compressed images.
- **Downloadable Output**: Provides the option to download the compressed image.

## 🛠️ Tech Stack

- **Python**: Core language for processing
- **Streamlit**: Web framework for UI
- **NumPy**: Image data manipulation
- **Scikit-learn (KMeans Clustering)**: Color clustering
- **PIL (Pillow)**: Image processing
- **io (BytesIO)**: In-memory file handling

## 📦 Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/pixel-reducer.git
   cd pixel-reducer
   ```
2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## ▶️ Usage

Run the application using Streamlit:

```sh
streamlit run app.py
```

Then, open the link generated by Streamlit in your browser.

## 💡 Use Cases

- **Web Optimization**: Reduce image sizes for faster website loading.
- **Digital Art & Design**: Create stylized posterized effects.
- **Data Visualization**: Extract dominant colors from an image.
- **Mobile & App Development**: Optimize images for storage and performance.

## 🏗️ Future Improvements

- Support for more image formats (WebP, TIFF, etc.)
- Additional compression techniques for better optimization
- Batch processing for multiple images

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch (`feature-new`).
3. Commit your changes (`git commit -m "Added new feature"`).
4. Push to your branch (`git push origin feature-new`).
5. Create a pull request.

---

⭐ **Star this repo if you find it useful!** 😊

