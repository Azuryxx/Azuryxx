# 👋 Hello, I'm Azuryxx!  



```markdown
# Profil de Développeur - Azuryx 👨‍💻

Découvrez mon parcours dans le dev et mes compétences en programmation !

```csharp
using System;

public class DeveloperProfile
{
    public string Name = "Azuryx";
    public string Status = "Étudiant en Informatique 🎓";
    public string Level = "Débutant en dev";
    public string[] Languages = { "Python 🐍", "C# 💻", "HTML", "CSS",  };
    public string[] Learning = { "Frontend (HTML, CSS, JavaScript)", "Backend (Node.js, Python, Django)" };

    // Outils utilisés
    public string[] Tools = { "VS Code 👨‍💻", "PyCharm 🖥️", "Git 🔧", "Linux 🐧" };

    public string Introduce()
    {
        return $"Salut, je suis {Name}, {Status}. J'apprends {string.Join(", ", Languages)}!";
    }

    public string ToolsUsed()
    {
        return $"Je travaille avec des outils comme {string.Join(", ", Tools)}.";
    }

    public static void Main(string[] args)
    {
        DeveloperProfile me = new DeveloperProfile();
        Console.WriteLine(me.Introduce());
        Console.WriteLine(me.ToolsUsed());  
    }
}

    {
        DeveloperProfile me = new DeveloperProfile();
        Console.WriteLine(me.Introduce());
        Console.WriteLine(me.ToolsUsed());  
    }
}
