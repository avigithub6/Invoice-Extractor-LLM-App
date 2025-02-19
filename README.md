# MultiLanguage Invoice Extractor

## 📌 Project Overview
This project is a **Streamlit web application** that extracts and interprets invoice details using **Google Gemini AI (gemini-1.5-flash)**. Users can upload invoice images and ask questions related to the extracted information.

---

## 🚀 Features
- **Upload Invoice Images**: Supports JPG, JPEG, and PNG formats.
- **AI-Powered Extraction**: Uses **Google Gemini API** to interpret invoice details.
- **User Query Support**: Ask questions related to the uploaded invoice.
- **Streamlit UI**: Simple and interactive interface.

---

## 📂 Files in Repository
- **app.py**: The main application script.
- **.env**: Stores API keys (not included in the repo).
- **requirements.txt**: Lists required Python dependencies.
- **README.md**: Documentation for setup and usage.

---

## 🛠️ Technologies Used
- **Python**
- **Streamlit** (UI Framework)
- **Google Gemini AI** (LLM API)
- **PIL (Pillow)** (Image Processing)

---

## 🔧 Installation & Setup

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/yourusername/invoice-extractor.git
cd invoice-extractor
```

2️⃣ **Create a Virtual Environment** (Recommended)
```sh
python -m venv myenv
```

3️⃣ **Activate the Virtual Environment**
- **Windows (PowerShell):**
  ```sh
  myenv\Scripts\Activate.ps1
  ```
- **Mac/Linux:**
  ```sh
  source myenv/bin/activate
  ```

4️⃣ **Install Dependencies**
```sh
pip install -r requirements.txt
```

5️⃣ **Set Up API Key**
- Create a `.env` file and add:
  ```sh
  GOOGLE_API_KEY=your_actual_api_key_here
  ```

6️⃣ **Run the Application**
```sh
streamlit run app.py
```

---

## 📸 How It Works
1. **Upload an invoice image (JPG, PNG, JPEG).**
2. **Enter a query related to the invoice.**
3. **Click 'Tell me about the invoice'.**
4. **View AI-generated responses based on the invoice details.**

---

## ⚠ Troubleshooting
### 1️⃣ API Key Not Found
Check if `.env` contains a valid API key and restart VS Code.
```sh
import os
print(os.getenv("GOOGLE_API_KEY"))
```

### 2️⃣ Streamlit App Not Running
Make sure you are in the correct project folder and run:
```sh
streamlit run app.py
```

---

## 📜 License
This project is **open-source** under the MIT License.

---

## 🤝 Contributing
Pull requests are welcome! Feel free to submit issues and feature requests.

---

