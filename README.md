I'm still editing to make it more efficient for research papers (if you are interested in working on this, ping me at vasudevakarina@gmail.com)

# TechSpeak

TechSpeak is a Flask-based web application that processes technical documents, interprets formulas, and converts the content to speech. It's designed to make technical content more accessible, especially for people with disabilities.

## Features

- Supports PDF, DOCX, and TXT files
- Interprets mathematical formulas
- Converts processed text to speech

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/techspeak.git
   cd techspeak
   ```

2. Install the required packages:
   ```
   pip install flask gTTS sympy PyPDF2 python-docx
   ```

## Usage

1. Run the Flask application:
   ```
   python app.py
   ```

2. Open a web browser and go to `http://localhost:5000`

3. Upload a document and receive the processed audio file

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Flask](https://flask.palletsprojects.com/)
- [gTTS](https://gtts.readthedocs.io/)
- [SymPy](https://www.sympy.org/)
- [PyPDF2](https://pythonhosted.org/PyPDF2/)
- [python-docx](https://python-docx.readthedocs.io/)
