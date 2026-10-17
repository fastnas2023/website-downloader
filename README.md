# 🌐 Website Downloader

Website Downloader is a powerful Python script designed to download entire websites along with all their assets. This tool allows you to create a local copy of a website, including HTML pages, images, CSS, JavaScript files, and other resources. It ensures that all internal links and resources are downloaded for offline viewing. Perfect for web archiving and offline browsing!

## ✨ Features

- 🔄 Recursively download entire websites.
- 💾 Save HTML pages with all linked assets.
- 🔗 Convert links for offline viewing.
- 🖼️ Handle various file types including images, CSS, and JavaScript.
- 📜 Log download progress and errors.
- ✔️ Verify the completeness of the downloaded website and re-download missing files if necessary.

## 📥 Installation

1. Clone the repository:
   
   ```bash
   git clone https://github.com/PKHarsimran/website-downloader.git
   cd website-downloader
   ```
2. Install the required dependencies:
   
   ```bash
    pip install -r requirements.txt
   ```

## 🚀 Usage

1. Run the website downloader script:
   ```bash
   python website-downloader.py
   ```
2. Follow the prompts to enter the URL of the website to download and the destination folder.
3. After the download is complete, you will be prompted to check if the website is correctly downloaded.


## 🛠️ Libraries Used

- **requests**: 🌐 A simple and elegant HTTP library for Python. Used to send HTTP requests to download HTML pages and resources.
- **wget**: 📥 A utility for non-interactive download of files from the web. Used to download resources such as images, CSS, and JavaScript files.
- **BeautifulSoup**: 🍜 A library for parsing HTML and XML documents. Used to extract links to resources from HTML pages.
- **logging**: 📝 A standard Python library for generating log messages. Used to log download progress and errors.
- **subprocess**: ⚙️ A standard Python library to spawn new processes, connect to their input/output/error pipes, and obtain their return codes. Used to run the verification script.
- **argparse**: 🛠️ A standard Python library for parsing command-line arguments. Used in the verification script to handle input parameters.

## 🗂️ Project Structure

- `website-downloader.py`: The main script for downloading the website and its resources.
- `check_download.py`: The verification script for checking the completeness of the downloaded website.
- `requirements.txt`: A file listing the required dependencies.

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## 📜 License

This project is licensed under the MIT License.

<!-- fastnas2023-support:start -->
## 支持 fastnas2023 / Support

如果你愿意支持 **fastnas2023**，可以通过微信或支付宝自愿打赏。感谢支持！

If you would like to support **fastnas2023**, you can optionally donate via WeChat Pay or Alipay. Thank you!

<p align="center">
  <img src="https://raw.githubusercontent.com/fastnas2023/fastnas2023/9dbfee7325a5e86d89a28c8d1bf95497005f40c7/assets/donate.png" alt="fastnas2023 微信和支付宝打赏码 / WeChat Pay and Alipay donation QR codes" width="700" />
</p>

[GitHub · fastnas2023](https://github.com/fastnas2023)
<!-- fastnas2023-support:end -->
