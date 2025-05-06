# FusionIQ

FusionIQ is an advanced AI integration platform that combines multiple artificial intelligence tools and capabilities into a unified solution. This project aims to provide a seamless experience for developers working with various AI technologies.

## 🌟 Features

- **RAG Integration**: Robust Retrieval-Augmented Generation capabilities
- **CrewAI Support**: Integration with CrewAI for enhanced AI agent collaboration
- **FastAPI Implementation**: High-performance API endpoints
- **Environment Management**: Secure configuration handling with `.env` support
- **Graph Processing**: Advanced graph-based data processing capabilities

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- Git

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/RohitMudili/FusionIQ.git
   cd FusionIQ
   ```

2. **Set Up Virtual Environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On Unix or MacOS
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables**
   ```bash
   cp .env.example .env
   # Edit .env file with your configuration
   ```

## 📁 Project Structure

```
FusionIQ/
├── RAG/
│   └── chunk_extractor.py    # RAG implementation components
├── .env.example              # Example environment configuration
├── crewai_doc.md            # CrewAI documentation
├── crewai_fastapi.py        # FastAPI integration with CrewAI
├── graph.py                 # Graph processing utilities
└── requirements.txt         # Project dependencies
```

## 🛠️ Usage

### RAG Implementation
The RAG (Retrieval-Augmented Generation) module provides advanced text processing capabilities:
- Document chunking
- Information retrieval
- Context-aware generation

### CrewAI Integration
Leverage the power of AI agents working together:
- Multi-agent collaboration
- Task orchestration
- Automated workflows

### FastAPI Endpoints
The project includes RESTful API endpoints for:
- AI model interactions
- Data processing
- System integration

## 🔧 Configuration

Configure your environment variables in the `.env` file:
- API keys
- Service endpoints
- System parameters

## 📚 Documentation

- Detailed API documentation available in `crewai_doc.md`
- Implementation examples and use cases
- Best practices and guidelines

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- CrewAI team for their excellent framework
- FastAPI community for the robust API framework
- All contributors who have helped shape this project

## 📞 Contact

Rohit Mudili - [GitHub Profile](https://github.com/RohitMudili)

Project Link: [https://github.com/RohitMudili/FusionIQ](https://github.com/RohitMudili/FusionIQ) 