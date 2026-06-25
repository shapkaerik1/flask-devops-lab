# Flask DevOps Lab

## Usage

Activate the virtual environment, install requirements, and run the app:

```bash
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## API Routes

- `/api/health` - Returns a JSON health check status of the app
- `/api/config` - Returns the current app configuration from config.json
- `/api/report` - Returns hostname, Python version, and app uptime in seconds
