# pubg-api-experiment

![PUBG API experiment](script.gif)

Experimenting with the [PUBG](https://developer.pubg.com/) API. The script prints a curated list of statistics for specified players by retrieving data from [api.pubg.com](https://api.pubg.com).

## Requirements

- Python 3.8.x
- A PUBG developer API key (see instructions below)
- [pipenv](https://github.com/pypa/pipenv)

## Use the script

Retrieve a development API key from [developer.pubg.com](https://developer.pubg.com/) (you need to sign-up with your PUBG account).

Create a file named `secret.json` and put your newly generated API key in the following format.

```json
{
    "api_key": "API key here!"
}
```

Make sure you have [pipenv](https://github.com/pypa/pipenv) installed.

Install all dependencies.

```bash
pipenv install
```

Enter the shell of the pipenv environment.

```bash
pipenv shell
```

Run the Python script.

```bash
python app.py
```

## Author

Script was written by [Vilhelm Prytz](https://github.com/VilhelmPrytz).
