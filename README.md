# Shipment Assistance Bot

## 📌 Description
The **Shipment Assistance Bot** is an AI-powered chatbot designed to assist users with shipping queries, tracking updates, and estimated delivery times. This intelligent assistant leverages natural language processing (NLP) and vector search to provide accurate and real-time responses.

## 🚀 Technologies Used
- **Backend:** Flask (Python)
- **AI Model:** Ollama (Mistral) for AI-generated responses
- **Vector Search:** FAISS for shipment retrieval
- **Database:** Currently using a dictionary (can be extended with MongoDB/PostgreSQL)
- **CORS Support:** Enabled for seamless frontend integration

## 🔥 Features
- AI-driven shipment query handling
- Real-time order tracking assistance
- Retrieval-based responses using FAISS
- Easily extendable database for storing shipment data
- Secure CORS-enabled API for frontend interaction

## 🛠 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/Shipment-Assistance-Bot.git
cd Shipment-Assistance-Bot
```

### 2️⃣ Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Flask Server
```bash
python app.py
```
The server should now be running on `http://127.0.0.1:5000`.

## 💡 Future Enhancements
- Integration with MongoDB/PostgreSQL for persistent data storage
- Advanced AI models for more accurate responses
- Voice and multilingual support
- Secure user authentication & authorization

## 🤝 Contribution
We welcome contributions! Feel free to fork this repository and submit pull requests.


