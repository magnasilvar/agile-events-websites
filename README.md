# Agile Events Websites

This repository contains a collection of websites I created for past agile events, providing event-specific resources to support participants.

## Event Websites

1. [PACK Agile Games Day 2021](pagd21/README.md): Schedule for game masters at this one-day event.
2. [XP Game](xpgame/README.md): US (User Stories) acceptance criteria, for coaches.

## Features

* **Self-contained:** All files are static, requiring no external dependencies.
* **Lightweight:** Built with pure HTML and CSS for simplicity.
* **Flexible Deployment:** Open locally or serve via any HTTP server.

## How to Use

Clone or download the repository:
```bash
git clone https://github.com/magnasilvar/agile-events-websites.git
```

### Option 1: Open Locally

Open any `.html` file in a web browser. No setup needed.

### Option 2: Serve with an HTTP Server

Use your preferred HTTP server to host the files. Examples:
* **Python 3**:
  ```bash
  python -m http.server
  ```
  Then, open http://localhost:8000 in your browser.
* **Node.js** (requires [http-server](https://www.npmjs.com/package/http-server)):
  ```bash
  npx http-server .
  ```
  Then, open http://localhost:8080 in your browser.
