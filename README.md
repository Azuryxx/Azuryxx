# 👋 Hello, I'm Azuryxx!  



```markdown
# Profil de Développeur - Azuryx 👨‍💻

Découvrez mon parcours de développeur C# et mes compétences en programmation !

```csharp
using System;

public class DeveloperProfile
{
    public string Name = "Azuryx";
    public string Status = "Étudiant en Informatique 🎓";
    public string Level = "Débutant en C#";
    public string[] Languages = { "Python 🐍","C# 💻", "HTML", "CSS" };
    public string[] Learning = { "Unity3D", "Développement de jeux vidéo" };

    public string Introduce()
    {
        return $"Salut, je suis {Name}, {Status}. J'apprends {string.Join(", ", Languages)}!";
    }

    public static void Main(string[] args)
    {
        DeveloperProfile me = new DeveloperProfile();
        Console.WriteLine(me.Introduce());
    }
}

# Affichage de la bio
print(me.intro())
print(me.languages_used())
print(me.framework_expertise())
print(me.tools_i_use())
print(me.interests_and_learning())
print(me.contact_info())
