# alex

A simple web app for voice interaction — allows capturing voice input and doing something with it.  
Built with HTML, CSS, JavaScript.

---

## Table of Contents

- [Features](#features)  
- [Getting Started](#getting-started)  
- [Prerequisites](#prerequisites)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Technologies Used](#technologies-used)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Features

- Captures voice (microphone) input  
- Possibly visual feedback/animation (e.g. microphone icon or voice gif)  
- Basic styling with CSS for interface  

---

## Getting Started

These instructions will help you run this project locally.

### Prerequisites

- A modern web browser that supports Web Speech API (or relevant voice recognition features)  
- Local web server (optional but recommended for avoiding issues with file:// protocol)  

### Installation

1. Clone the repo:

   ```bash
   git clone https://github.com/Moneyy02/alex.git
   cd alex

Usage
Open index.html in the browser (or access via http://localhost:8000/index.html if using a local server).

Grant microphone permissions when prompted.

Interact via voice (e.g. speak, record) and see the feedback or response on screen.

Project Structure
bash
Copy code
alex/
├── index.html      # main HTML page

├── style.css       # styling for UI

├── main.js         # core JavaScript logic

├── script.js       # possibly additional JS (event-handling, etc.)

├── mic.svg         # microphone icon graphic

├── voice.gif       # visual animation for voice capture/feedback

└── ...             # any other assets

Technologies Used
HTML5

CSS3

JavaScript (ES6+)

Web Speech / Media APIs (for voice/mic input)
