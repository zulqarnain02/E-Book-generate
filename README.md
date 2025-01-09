# 📚 AI-Powered E-Book Generator

Welcome to the **AI-Powered E-Book Generator**! 🚀 This project leverages the power of AI to create Markdown-based content and convert it into beautifully styled PDFs. Whether you're creating a GitHub README or a professional e-book, this tool has you covered. 💡

---

## 🌟 Features

- ✨ Generate detailed content using AI.
- 📝 Save the content directly as a `README.md` file.
- 📄 Convert Markdown files to professionally styled PDFs.
- 🎨 Includes GitHub-like CSS styling for PDFs.

---

## 🛠️ How It Works

### 1. Dependencies

Ensure the following dependencies are installed:

```bash
sudo apt-get install -y python3-cffi libcairo2 libpango-1.0-0 libgdk-pixbuf2.0-0 libffi-dev shared-mime-info
pip install requests markdown2 weasyprint
```

### 2. Generate Content

Provide a topic and additional description. The tool interacts with an AI API to create detailed content based on your inputs. ✍️

### 3. Save as Markdown

The generated content is saved as `README.md` for easy use in GitHub repositories. 🗂️

### 4. Convert to PDF

Using the `WeasyPrint` library, the Markdown content is converted to a styled PDF, ideal for sharing and documentation. 📑

---

## 🔧 Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/ai-ebook-generator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ai-ebook-generator
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Replace `YOUR GEMINI API KEY` with your actual API key in the script.

---

## 💻 Usage

Run the script using Python:

```bash
python3 generate_ebook.py
```

1. Enter a topic for the e-book.
   
   ![Screenshot 2025-01-10 032429](https://github.com/user-attachments/assets/73870a2f-fe73-41d6-a289-6783f9ec4c2b)
 
2. Provide additional details to include in the content.
   
   ![Screenshot 2025-01-10 032444](https://github.com/user-attachments/assets/1496d018-8e69-4d62-876a-903df58bc681)

3. The tool generates a `README.md` file and a PDF with the topic name.

---

## 📁 Example Directory Structure

```
ai-ebook-generator/
├── generate_ebook.py
├── README.md
├── example.pdf
└── requirements.txt
```

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details. ⚖️

---

## 🚀 Future Enhancements

- 🌐 Support for multiple languages.
- 📦 Integration with cloud storage for saving e-books.
- 🎨 Customizable PDF themes.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you'd like to change. 🙌

---

## 💌 Contact

For queries or support, feel free to reach out:
- Email: your.email@example.com 📧
- GitHub: [Your GitHub Profile](https://github.com/your-profile) 🌐

---

Happy E-Book Generating! 🎉
