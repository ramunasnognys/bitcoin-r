# Bitcoin-R

A comprehensive Bitcoin data analysis and visualization platform built with Python.

## Overview

Bitcoin-R provides tools for analyzing Bitcoin blockchain data, market trends, and creating visualizations to help understand cryptocurrency patterns and behaviors. This repository contains the codebase for both backend data processing and frontend visualization components.

## Features

- Real-time Bitcoin price tracking
- Historical data analysis
- Blockchain transaction analysis
- Interactive data visualizations
- Market trend predictions
- Customizable dashboards

## Tech Stack

- **Backend**: Python
- **Frontend**: HTML/JavaScript
- **Database**: SQL (PostgreSQL)
- **Search**: Elasticsearch
- **Testing**: Python unittest framework

## Project Structure

```
bitcoin-r/
├── backend/          # Python backend code
├── frontend/         # HTML/JS frontend code
├── database/         # Database schemas and migrations
├── tests/            # Test suite
├── docs/             # Documentation
└── requirements.txt  # Python dependencies
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/ramunasnognys/bitcoin-r.git
   cd bitcoin-r
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Configure environment variables (create a `.env` file based on `.env.example`)

4. Run the application:
   ```
   python app.py
   ```

## Development

The project maintains separate environments for development, testing, and production, each with its own database configuration.

## Testing

Run the test suite:
```
python -m unittest discover tests
```

## License

MIT

## Contact

For questions or feedback, please open an issue in the repository.