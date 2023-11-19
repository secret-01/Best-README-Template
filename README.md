# Log Project

## Overview

The Log Project is a system for ingesting and querying log data. It consists of a Log Ingestor that efficiently handles log data and stores it in both MySQL and MongoDB databases. The Query Interface provides a user-friendly web interface for searching logs based on various criteria.

## Features

- **Log Ingestor:**
  - Ingests logs in the provided format over HTTP.
  - Stores logs in MySQL and MongoDB databases.
  - Ensures scalability to handle high volumes of logs efficiently.

- **Query Interface:**
  - Provides a web interface for full-text search across logs.
  - Supports filters based on log attributes.
  - Aims for efficient and quick search results.

## Installation

### Prerequisites

- Python 3.x
- MongoDB (version X.X.X)
- MySQL (version X.X.X)

### Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/log-project.git
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up and start MongoDB and MySQL servers.

4. Configure MySQL credentials in `log_ingestor.py` and `query_interface.py`.

## Usage

### Log Ingestor

Run the Log Ingestor:

```bash
python log_ingestor.py
