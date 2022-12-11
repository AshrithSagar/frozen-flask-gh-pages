# frozen-flask-gh-pages
> Host Frozen-Flask on GitHub Pages

- Flask
  https://flask.palletsprojects.com/

- Frozen-Flask
https://pythonhosted.org/Frozen-Flask/

- GitHub Pages
https://pages.github.com/

## How to use

1. Fork the repository

2. Create a new branch called `gh-pages`.

3. Configure GitHub Pages to deploy from any branch [Default: `gh-pages`].

   *Important:* Set directory to `docs/`.

   ![GitHub Pages Settings config](assets/github.com_AshrithSagar_frozen-flask-gh-pages_settings_pages.png)

4. Create a virtual environment and install dependencies
   ```python3 -m venv .venv```

   `. .venv/bin/activate`

   `pip install -r requirements.txt`

5. Run the server
   `python3 app.y`

6. The static website files are stored in `docs/` directory, which will be hosted on GitHub Pages.

## License

MIT License
