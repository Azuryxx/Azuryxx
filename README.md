# 👋 Hello, I'm Azuryxx!  

class DeveloperBio:
    def __init__(self):
        self.name = "Azuryx"
        self.title =   Étudiant en Informatique 🎓
        self.languages = ["Python 🐍", " basse du C# 🎮", "HTML & CSS ✨"]
        self.frameworks = [ "Node.js"]
        self.tools = ["Git 🔧", "PyCharm 🖥️", "VS Code 👨‍💻", "Linux 🐧"]
        self.interests = ["Développement Web", "Basse de Donnée", "Sécurité Informatique"]
        self.current_project = "Apprendre le Machine Learning 📚"
        self.contact = "azuryy_"

    def intro(self):
        return f"Salut, je suis {self.name}, un passionné de programmation qui apprend et explore sans cesse des nouvelles technologies. 🚀"
    
    def languages_used(self):
        return f"J'utilise des langages comme {', '.join(self.languages)}."
    
    def framework_expertise(self):
        return f"Je travaille avec des frameworks tels que {', '.join(self.frameworks)}."
    
    def tools_i_use(self):
        return f"Mes outils favoris incluent {', '.join(self.tools)}."
    
    def interests_and_learning(self):
        return f"Je m'intéresse à {', '.join(self.interests)} et mon projet actuel est de {self.current_project}."
    
    def contact_info(self):
        return f"Si tu veux discuter ou collaborer : {self.contact}"

# Création de la bio
me = DeveloperBio()

# Affichage de la bio
print(me.intro())
print(me.languages_used())
print(me.framework_expertise())
print(me.tools_i_use())
print(me.interests_and_learning())
print(me.contact_info())
