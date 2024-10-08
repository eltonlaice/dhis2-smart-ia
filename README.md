# DHIS2 Smart IA

<p align="center">
  <img src="https://dhis2.org/wp-content/uploads/dhis2-logo-rgb-positive.svg" alt="DHIS2 Smart IA Logo">
</p>

<p align="center">
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/stargazers"><img src="https://img.shields.io/github/stars/eltonlaice/dhis2-smart-ia" alt="Stars Badge"/></a>
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/network/members"><img src="https://img.shields.io/github/forks/eltonlaice/dhis2-smart-ia" alt="Forks Badge"/></a>
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/pulls"><img src="https://img.shields.io/github/issues-pr/eltonlaice/dhis2-smart-ia" alt="Pull Requests Badge"/></a>
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/issues"><img src="https://img.shields.io/github/issues/eltonlaice/dhis2-smart-ia" alt="Issues Badge"/></a>
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/eltonlaice/dhis2-smart-ia?color=2b9348"></a>
  <a href="https://github.com/eltonlaice/dhis2-smart-ia/blob/master/LICENSE"><img src="https://img.shields.io/github/license/eltonlaice/dhis2-smart-ia?color=2b9348" alt="License Badge"/></a>
</p>

<p align="center">
  <i>Intelligent Artificial Intelligence for your DHIS2 (District Health Information Software 2)</i>
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#how-it-works">How It Works</a> •
  <a href="#getting-started">Getting Started</a> •
  <a href="#usage">Usage</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a> •
  <a href="#contact">Contact</a>
</p>

## Overview

DHIS2 Smart IA is an innovative Flask-based project that integrates DHIS2 (District Health Information Software 2) with OpenAI to provide intelligent responses to health-related questions based on DHIS2 data.

This project creates a bridge between DHIS2, a widely used health information management system, and OpenAI's powerful language models. By leveraging the vast amount of health data stored in DHIS2 and the natural language processing capabilities of OpenAI, DHIS2 Smart IA enables users to ask health-related questions and receive informed answers based on real data.

## Features

- 🔗 Seamless integration with DHIS2 for accessing health-related data
- 🧠 Utilization of OpenAI's language models for natural language processing
- 🖥️ User-friendly interface for asking health-related questions
- 📊 Data-driven responses based on DHIS2 information
- 🌐 RESTful API for easy integration with other systems

## How It Works

1. Users input health-related questions through the application interface.
2. The system processes the questions using OpenAI's language models.
3. Relevant data is retrieved from the DHIS2 database.
4. The AI generates informative responses based on the DHIS2 data and the user's query.
5. The answer is presented to the user in a clear and understandable format.

## Getting Started

### Prerequisites

- Python 3.8+
- Flask
- DHIS2 instance
- OpenAI API key

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/eltonlaice/dhis2-smart-ia.git
   cd dhis2-smart-ia
   ```

2. Install required packages:
   ```sh
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```sh
   cp .env.example .env
   ```
   Edit the `.env` file with your DHIS2 and OpenAI credentials.

4. Run the application:
   ```sh
   flask run
   ```

## Usage

(Add instructions on how to use the application, including examples of queries and expected outputs)

```python
# Example code for using the API
import requests

url = "http://localhost:5000/api/query"
payload = {"question": "What is the COVID-19 vaccination rate in district X?"}
response = requests.post(url, json=payload)

print(response.json())
```

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Elton Laice - [@eltonlaice](https://www.linkedin.com/in/eltontlaice/) - meu@eltonlaice.com

Project Link: [https://github.com/eltonlaice/dhis2-smart-ia](https://github.com/eltonlaice/dhis2-smart-ia)

---

<p align="center">
  Developed with ❤️ by <a href="https://www.linkedin.com/in/eltontlaice/">Elton Laice</a>
</p>