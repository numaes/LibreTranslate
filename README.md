# LibreTranslate

Free and Open Source Translation API.

Entirely self-hosted and can work in offline environments. Unlike other APIs, it doesn't rely on proprietary providers such as Google or Azure to perform translations.

![image](https://user-images.githubusercontent.com/1951843/102724116-32a6df00-42db-11eb-8cc0-129ab39cdfb5.png)

[Try it online!](https://libretranslate.com) | [API Docs](https://libretranslate.com/docs)

Website: [libretranslate.com](https://libretranslate.com)

## Build and Run

Make sure you have installed Python (3.8 or higher), then simply issue:

```bash
git clone https://github.com/uav4geo/LibreTranslate --recurse-submodules
cd LibreTranslate
pip install -r requirements.txt
python main.py [args]
```

## Arguments

| Argument      | Description                    | Default              |
| ------------- | ------------------------------ | -------------------- |
| --host        | Set host to bind the server to | `127.0.0.1`          |
| --port        | Set port to bind the server to | `5000`               |
| --char-limit        | Set character limit | `No limit`               |
| --req-limit        | Set maximum number of requests per minute per client | `No limit`               |
| --ga-id        | Enable Google Analytics on the API client page by providing an ID | `No tracking`               |
| --debug      | Enable debug environment | `False`           |
| --ssl        | Whether to enable SSL | `5000`               |


## Roadmap

Help us by opening a pull request!

- [ ] A docker image
- [ ] Auto-detect input language
- [ ] User authentication / tokens

## Credits

This work is largely possible thanks to [Argos Translate](https://github.com/argosopentech/argos-translate), which powers the translation engine.

## License

[GNU Affero General Public License v3](https://www.gnu.org/licenses/agpl-3.0.en.html)