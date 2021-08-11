```python
from __future__ import annotations

import json
from dataclasses import asdict, dataclass


@dataclass
class Me:
    languages: tuple[str, ...] = ("PHP", "Python", "JS", "TypeScript")
    databases: tuple[str, ...] = ("MYSQL", "PostgreSQL", "Mongo", "Redis")
    misc     : tuple[str, ...] = ("Docker", "Celery", "RabbitMQ", "Arq", "SQS")
    ongoing  : tuple[str, ...] = ("Symfony", "Django", "Laravel", "NestJS", "Flask")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)
        
me = Me()
print(me.jsonify())

```
