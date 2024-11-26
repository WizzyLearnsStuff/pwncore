# pwncore

A CTF platform backend written in [FastAPI](https://github.com/fastapi/fastapi) using [Tortoise-ORM](https://github.com/tortoise/tortoise-orm), [Tox](https://github.com/tox-dev/tox) and [Pydantic](https://github.com/pydantic/pydantic)

## Usage

1. Start:

   ```bash
   cd src
   uvicorn pwncore:app --reload
   ```

2. Access the auto-generated documentation at [http://localhost:8000/docs](http://localhost:8000/docs)

3. Docker configuration:
   - Enable and start the Docker service on your system, or
   - Modify `src/pwncore/config.py:62`:

## License

This project is licensed under the [GNU GENERAL PUBLIC LICENSE] - see the [LICENSE](./LICENSE) file for details.
