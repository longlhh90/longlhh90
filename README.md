# 👋 Hi, I’m Lukas
[![Linkedin](https://img.shields.io/badge/LukasLe-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/l0ng-le/)](https://www.linkedin.com/in/l0ng-le/)
![visitors](https://visitor-badge.glitch.me/badge?page_id=${longlhh90})
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
      # "human": ["English", "Vietnamese"],
      "computer": ["Python", "Javascript", "Java"]
    },
    frameworks = ["django", "flask", "angular", "javascript", "expressjs", "nestjs"],
    tools = ["vscode", "pycharm", "docker", "jira", "trello", "google tools"],
    os = ["macOS", "linux", "windows"],
    hobbies = ["coding", "data analyzing", "working out", "travelling"]
  )
  pprint.pprint(vars(me))
```

