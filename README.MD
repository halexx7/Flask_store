# Простой интернет-магазин на FLASK

```
python3 -m venv venv
source venv/bin/activate
```

.vscode/settings.json
```
{
    "python.pythonPath": "venv/bin/python",
    "python.languageServer": "Pylance",
    "python.experiments.optOutFrom": [
        "All"
    ],
    "python.testing.unittestArgs": [
        "-v",
        "-s",
        "./tests",
        "-p",
        "test_*.py"
    ],
    "python.testing.pytestEnabled": false,
    "python.testing.nosetestsEnabled": false,
    "python.testing.unittestEnabled": true,
}
```