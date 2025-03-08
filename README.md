# 👋 Hello, I'm Azuryx!  

```python
class DeveloperProfile:
    def __init__(self):
        self.name = "Azuryx"
        self.status = "Étudiant en Informatique 🎓"
        self.level = "Débutant en programmation"
        self.languages = ["Python 🐍", "Bases en C#"]
        self.learning = ["Développement logiciel", "Algo & structures de données"]

    def introduce(self):
        return f"Salut, je suis {self.name}, {self.status}. J'apprends {', '.join(self.languages)}!"

me = DeveloperProfile()
print(me.introduce())
