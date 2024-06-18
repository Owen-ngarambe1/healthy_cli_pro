# Health and Fitness Tracker CLI

## Overview

The Health and Fitness Tracker CLI project is a command-line interface application that allows users to log their daily activities, meals, and health metrics for effective health tracking and analysis.

## Features

- User registration
- Logging of activities (type, duration)
- Logging of meals (food items, nutritional information)
- Logging of health metrics (weight, sleep duration).
- Viewing daily summaries of activities, meals, and health metrics.

## Getting Started

### Prerequisites

- Pipenv (for virtual environment and package management)
- SqlAlchemy.

### Installation
e repository:
1
. Clone th
   ```bash
   git clone git@github.com:Owen-ngarambe1/healthy_cli_pro.git
   ```
2. Navigate to the project
    ```
    cd HEALTH CLI
    ```

3. Install dependencies 
    ``` 
    pipenv install 
    ```

## Database Setup
1. Initialize the database:

    ```
    pipenv run python3 -m alembic init alembic
    ```
2. Apply initial migrations:
    ```
    pipenv run python3 -m alembic upgrade head 
## Usage
1. Register User 
    ```
    pipenv run python3 cli.py register-user 
    ```
2. Log an activity
    ```
    pipenv run python3 cli.py add-activity
    ```
3. Log a meal 
    ```
    pipenv run python3 cli.py add-meal
    ```
4. Log health metrics
    ```
    pipenv run python3 cli.py add-health-metric 
    ```
5. Viewing summary 
    ```
    pipenv run python3 cli.py view-summary
    ```

## Author & License 
owen ngarambe & [MIT LICENSE](LICENSE).
### presentation link
https://calip.io/PdXgJERC#BE2329Rx
