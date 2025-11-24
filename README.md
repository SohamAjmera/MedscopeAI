# MedScope-AI: Medical Imaging AI Platform

MedScope-AI is a comprehensive medical imaging platform that combines artificial intelligence, 3D visualization, and clinical analysis tools to assist medical professionals and patients in understanding medical imaging data.

## 🌟 Key Features

### 🧠 AI-Powered Medical Assistant
- Interactive chatbot powered by Google Gemini AI
- Specialized in medical imaging, radiology, and clinical questions
- Can interpret medical reports and explain complex findings
- Available 24/7 for medical education and guidance

### 📊 2D to 3D Medical Visualization
- Transform medical imaging data (MRI, CT, etc.) into interactive 3D models
- Supports multiple medical imaging formats (NIfTI, DICOM, MHD, NRRD)
- Real-time 3D rendering with adjustable visualization parameters
- Powered by MONAI, NiBabel, and PyDICOM libraries

### 📈 Medical Report Analyzer
- AI-powered analysis for MRI, CT scans, and X-ray imaging
- Detailed risk assessment with clinical recommendations
- Automatic report generation with PDF export capability
- Support for multiple imaging modalities:
  - MRI Analysis
  - CT Scan Analysis
  - X-Ray Analysis
  - Mammography Analysis
  - Sonography Analysis

### 👥 User Dashboards
- Separate interfaces for doctors and patients
- Secure authentication system
- Personalized medical data management
- Collaboration tools for medical teams

## 🏗️ Technical Architecture

### Frontend
- Built with React, TypeScript, and Vite
- Modern UI with Tailwind CSS styling
- Interactive components using Framer Motion
- 3D visualization with Plotly.js
- Responsive design for all device sizes

### Backend
- Python Flask API server
- Medical imaging processing with MONAI, NiBabel, PyDICOM
- AI capabilities powered by Google Gemini API
- Database management with SQLAlchemy
- RESTful API architecture

### Key Libraries & Technologies
- **Frontend**: React, TypeScript, Vite, Tailwind CSS, Plotly.js
- **Backend**: Python, Flask, MONAI, NiBabel, PyDICOM, Google Gemini API
- **Database**: SQLite (development), PostgreSQL (production)
- **Authentication**: Appwrite SDK
- **Visualization**: Plotly.js for 3D medical imaging

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Python (v3.8 or higher)
- pip or uv package manager
- Google Gemini API key (for AI features)

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/SohamAjmera/MedscopeAI.git
cd MedscopeAI
```

2. **Install frontend dependencies:**
```bash
npm install
```

3. **Install backend dependencies:**
```bash
cd backend
pip install -r requirements.txt
```

4. **Set up environment variables:**
Create a `.env` file in the backend directory with your Google Gemini API key:
```env
GOOGLE_API_KEY=your_gemini_api_key_here
```

### Running the Application

1. **Start the backend server:**
```bash
cd backend
sh start-backend.sh
```

2. **Start the frontend development server:**
```bash
npm run dev
```

3. **Access the application:**
Open your browser and navigate to `http://localhost:5173`

## 📁 Project Structure

```
MedScope-AI/
├── src/                 # Frontend React application
│   ├── components/      # UI components
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API service clients
│   └── ...
├── backend/             # Backend Python application
│   ├── app/             # Flask API server
│   │   ├── api/         # API routes
│   │   ├── services/    # Business logic
│   │   └── models.py    # Database models
│   ├── 2dTo3d/          # 2D to 3D visualization module
│   └── scan_report/     # Medical report analysis module
├── package.json         # Frontend dependencies
└── requirements.txt     # Backend dependencies
```

## 🧪 Features in Detail

### 3D Medical Visualization
Transform 2D medical scans into interactive 3D models:
- Upload medical imaging files (NIfTI, DICOM, etc.)
- Real-time 3D rendering with adjustable parameters
- Multiple visualization modes
- Export capabilities for research and presentation

### Medical Report Analysis
Get AI-powered insights from medical imaging:
- Upload medical scans for automated analysis
- Receive detailed clinical findings and recommendations
- Risk assessment with urgency classification
- Treatment suggestions based on findings
- PDF report generation for sharing with healthcare providers

### AI Chat Assistant
Interact with an AI medical expert:
- Ask questions about medical imaging findings
- Get explanations of complex medical terminology
- Receive guidance on follow-up actions
- 24/7 availability for medical education

## 🔒 Security & Privacy

- Secure user authentication
- Data encryption in transit
- HIPAA-compliant design principles
- No patient data stored permanently
- All processing done locally when possible

## 🤝 Contributing

We welcome contributions to MedScope-AI! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For questions, suggestions, or support, please open an issue on GitHub or contact the development team.

## 🙏 Acknowledgments

- MONAI for medical imaging AI frameworks
- Plotly.js for 3D visualization capabilities
- Google Gemini for AI-powered assistance
- All contributors and medical professionals who provided feedback

---

*MedScope-AI is designed for educational and research purposes. It is not intended to replace professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare providers for medical concerns.*
