<h2> Hi, I'm Juan Gabriel! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/ieyl9zmCjO4b4t6qoY/giphy.gif" width="230">
<p><em>Statistician at <a href="http://www.unb.br">Universidad de Antioquia</a><img src="https://media.giphy.com/media/fYSnHlufseco8Fh93Z/giphy.gif" width="30"></br>Data Visualization Analyst at <a href="https://emtelco.com.co/">Emtelco</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Linkedin: Juan Gabriel Colorado Restrepo](https://img.shields.io/badge/-JuanGabriel-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/juan-gabriel-colorado-restrepo-aaa053bb/)](https://www.linkedin.com/in/juan-gabriel-colorado-restrepo-aaa053bb/)
[![GitHub Juan Gabriel Colorado Restrepo](https://img.shields.io/github/followers/gabocr90?label=follow&style=social)](https://github.com/gabocr90)


### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...  

```python

from dataclasses import dataclass
from typing import Tuple


class Meta(type):
    def __new__(cls, name, bases, attrs):
        new_cls = super().__new__(cls, name, bases, attrs)
        return dataclass(unsafe_hash=True, frozen=True)(new_cls)


class Bio(metaclass=Meta):
    name        : str = "Juan Gabriel Colorado Restrepo"
    designation : str = "Data Scientist"
    company     : str = "Emtelco"
    base        : str = "Medellin, Colombia"


class Stack(metaclass=Meta):
    languages   : Tuple[str, ...] = ("Python", "R", "Shell")
    databases   : Tuple[str, ...] = ("MySQL", "PostgreSQL")
    misc        : Tuple[str, ...] = ("Excel", "Power BI")
    ongoing     : Tuple[str, ...] = ("Javascript", "HTML5", "CSS", "Django")

```

<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="60"> <em><b>I love connecting with different people</b> so if you want to say <b>hi, I'll be happy to meet you more!</b> :)</em>

---

⭐️ From [@gabocr90](https://github.com/gabocr90)

- 👋 Hi, I’m @gabocr90
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
gabocr90/gabocr90 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
