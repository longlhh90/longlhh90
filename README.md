# 👋 Hi, I’m Lukas
[![Linkedin](https://img.shields.io/badge/Lukas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/l0ng-le/)](https://www.linkedin.com/in/l0ng-le/)
### A Python About Me  

```Python
import pprint
import Developer

class Me(Developer):
  def __init__(self, name, job, languages, frameworks, tools, os, hobbies):
    super().__init__(languages, frameworks, tools, os)
    self.name = name
    self.job = job
    self.hobbies = hobbies
    
if __name__ == "__main__":
  me = Me(
    name = "Lukas Le",
    job = "Software Developer",
    languages = {
      # "human": ["English", "Tiếng Việt", "ein bisschen Deutsch"],
      "computer": ["Python", "Javascript", "Java", "any others"]
    },
    frameworks = ["django", "flask", "angular", "nexjs", "expressjs", "nestjs"],
    tools = ["nvim", "docker", "AWS", "GCP"],
    os = ["macOS", "linux", "windows"],
    hobbies = ["coding", "data analyzing", "working out", "travelling"]
  )
```

