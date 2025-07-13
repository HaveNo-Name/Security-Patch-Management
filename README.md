# Nmap CVE Scanner

A web application that analyzes Nmap XML scan results and identifies potential CVEs (Common Vulnerabilities and Exposures) for discovered services.

## Setup

1. Install Python dependencies:
```bash
pip install -r requirements.txt
```

2. Run the Flask application:
```bash
python app.py
```

3. Open your web browser and navigate to:
```
http://localhost:5000
```

## Usage

1. Upload an Nmap XML file using the web interface
2. The application will analyze the scan results and identify potential CVEs
3. View detailed information about discovered vulnerabilities and recommendations

## Features

- Parse Nmap XML scan results
- Search for CVEs based on service product and version
- Generate security recommendations
- Modern web interface with React
- Real-time processing feedback

## File Structure

- `app.py` - Flask backend server
- `static/index.html` - Frontend web interface
- `nmap_parser.py` - Nmap XML parsing logic
- `nvd_lookup.py` - CVE database lookup
- `llm_recommender.py` - Security recommendations
- `uploads/` - Temporary file storage 