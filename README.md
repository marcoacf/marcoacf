### Hi there 👋
[![Linkedin Badge](https://img.shields.io/badge/-marcoacf-blue?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/marcoacf/)](https://www.linkedin.com/in/marcoacf/)
[![Twitter Badge](https://img.shields.io/badge/-@marcoacf-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/marcoacf)](https://twitter.com/marcoacf)
[![Gmail Badge](https://img.shields.io/badge/-marcoacf-c14438?style=flat&logo=Gmail&logoColor=white&link=mailto:marcoacf@gmail.com)](mailto:marcoacf@gmail.com)



```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class gyro_gearloose:

    def __init__(self):
        self.name = "Marco Cruz"
        self.role = "Consultant"
        self.language_spoken = ["pt_BR"]
        
    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

me = gyro_gearloose()
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


## Latest tweet
[<img src="https://hcti.io/v1/image/c551d575-c4ee-4d81-a037-712351336b0a" width="400">](https://twitter.com/marcoacf/status/1323822384487534592)

![Github Stats](https://github-readme-stats.vercel.app/api?username=itgoyo&bg_color=30,e96443,904e95&title_color=fff&text_color=fff)

![](https://raw.githubusercontent.com/marcoacf/github-stats-transparent/output/generated/overview.svg)
![](https://raw.githubusercontent.com/marcoacf/github-stats-transparent/output/generated/languages.svg)



<!--
**marcoacf/marcoacf** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

