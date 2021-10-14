### Hi there 👋
[![Linkedin Badge](https://img.shields.io/badge/-marcoacf-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/marcoacf/)](https://www.linkedin.com/in/marcoacf/)
[![Twitter Badge](https://img.shields.io/badge/-@marcoacf-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/marcoacf)](https://twitter.com/marcoacf)
[![Gmail Badge](https://img.shields.io/badge/-marcoacf-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:marcoacf@gmail.com)](mailto:marcoacf@gmail.com)



```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class sidekick:

    def __init__(self):
        self.name = "Marco Cruz"
        self.role = "Consultant"
        self.language_spoken = ["pt_BR"]
        
    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

me = sidekick()
me.say_hi()

from __future__ import annotations
import json
from dataclasses import asdict, dataclass
@dataclass
class Arsenal:
    languages: tuple[str, ...] = ("Python", "R", "VBA", "DAX", "PHP")
    databases: tuple[str, ...] = ("SQLite", "PostgreSQL", "MySQL", "SQL Server", "Oracle")
    ongoing  : tuple[str, ...] = ("GCP", "Big Query")

    def jsonify(self) -> str:
        return json.dumps(asdict(self), indent=4)


arsenal = Arsenal()
print(arsenal.jsonify())
```
<img src="https://www.codeitbro.com/wp-content/uploads/2020/07/python-meme-1-replace-for-loop-with-numpy-function.jpg" width="400">

## Latest tweet
(https://twitter.com/marcoacf/status/1323822384487534592)

![Github Stats](https://github-readme-stats.vercel.app/api?username=marcoacf&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

<!--
**marcoacf/marcoacf** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

[<img src="" width="400">]
