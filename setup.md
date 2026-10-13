# Getting Started
## Prerequisites
- Python
- Git
- Visual Studio Code (recommended)
- A Google Gemini API key or Preferred Model API Key

Obtain an API key from Google AI Studio.

1. Clone the Repository
git clone <repository-url>
cd <repository-folder>

2. Create a Virtual Environment

3. From the project root, create an isolated Python environment:

python -m venv .venv

Activate it before installing dependencies or running the scanner.

Windows PowerShell:
.\.venv\Scripts\Activate.ps1

Windows Command Prompt:
.venv\Scripts\activate.bat

macOS / Linux:
source .venv/bin/activate

4. Install Dependencies

If the repository contains a requirements.txt file:

python -m pip install -r requirements.txt

5. Configure Your API Key

Create a .env file in the project root and add your own Gemini API key:

GOOGLE_API_KEY=your_actual_google_api_key


Open scanner.py and update the GOOGLE_API_KEY configuration with your own key if required by the current implementation.

Keep your credentials private. Never commit real API keys or your .env file to GitHub.

6. Run the Scanner

With the virtual environment activated and the API key configured, run:

python scanner.py <file_name>
> vulnerability.py is provided as an example test file that is vulnerable. It should return at least 4 vulnerabilities when ran. 


The precise arguments and input workflow depend on the current implementation. Consult the source code for any additional requirements.

## Engineering Considerations

This project explores several practical challenges involved in building AI-assisted developer tools:

- Translating AI-generated analysis into actionable security findings.
- Presenting risk in a way that supports prioritization and decision-making.
- Integrating an external AI service into a Python application.
- Managing configuration and API credentials in a local development environment.
- Designing for potential changes in AI model providers.
- Considering the limitations of AI-generated security assessments.

These considerations reflect my interest in building tools that connect technical capabilities with real-world operational needs.

#### Limitations & Responsible Use

This tool provides AI-assisted analysis and should not be treated as a replacement for established security testing practices.

AI-generated findings may contain false positives, overlook vulnerabilities, or recommend fixes that require modification. Findings should be reviewed and validated, and proposed changes should be tested before deployment.

Users should also consider the confidentiality of source code submitted to external AI services.

### Future Development Opportunities

Potential areas for continued development include:

Expanding vulnerability detection and classification.
Supporting batch scanning across Python projects.
Producing structured reports for security workflows.
Integrating with automated development and CI/CD pipelines.
Expanding support for alternative AI models.
Evaluating finding accuracy against established security tools and benchmarks.

These are potential enhancements, not claims about existing functionality.

# About the Developer

I am a self-taught security focused coder with over 10 years of corporate experience, building technical skills through hands-on projects and practical problem-solving.

My background informs how I approach software development: understanding the problem, considering the end user, prioritizing what matters, and building solutions with a clear purpose.

Projects like this allow me to combine that business perspective with Python development, AI integration, and security-focused problem-solving.

I am interested in opportunities where I can continue growing technically while contributing analytical thinking, business awareness, and a practical, solutions-oriented mindset.

# Disclaimer

This project is intended for educational, development, and AI-assisted security analysis purposes. It does not guarantee the detection of all vulnerabilities or establish that analyzed code is secure. Always validate findings and test recommended fixes before using them in production.