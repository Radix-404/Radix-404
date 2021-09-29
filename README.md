# Hi , I am Gustavo
Front-end Developer, Coffee lover.

I'm learning at the moment JavaScript

[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gustavo-silva-623987215/) 
[<img src = "https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white">](https://www.instagram.com/gustavo.048/) 
[<img src = "https://img.shields.io/badge/facebook-%231877F2.svg?&style=for-the-badge&logo=facebook&logoColor=white">](https://www.facebook.com/Gustavo.174/)

## Technologies & Tools
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Arsenal:
    languages: tuple[str, ...] = ("Python", "JS", "Go")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "DynamoDB", "Redis")
    misc     : tuple[str, ...] = ("Docker", "Celery", "RabbitMQ", "Arq", "SQS")
    ongoing  : tuple[str, ...] = ("Django", "DRF", "Asyncio")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


arsenal = Arsenal()
print(arsenal.jsonify())
![YOUR github stats](https://github-readme-stats.vercel.app/api?username=0NEHITKILL)
