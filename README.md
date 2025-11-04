![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=180&section=header&text=Daniella%20Caballero&fontSize=38&fontAlignY=35&animation=fadeIn)

```csharp
using System;
using System.Collections.Generic;

public static class Daniella
{
    // 🧠 Contact
    public static void Contact()
    {
        string github = "github.com/Daniella-Caballero";
        string email = "daniellacaballeroo@gmail.com";
        string discord = "daniella.dev";

        Console.WriteLine($"GitHub: {github}\nEmail: {email}\nDiscord: {discord}");
    }

    // 🌍 About
    public static void About()
    {
        string[] langs = { "English", "Spanish", "Catalan" };
        string nationality = "Spaniard";
        string role = "Game Developing Enjoyer & Humor Enthusiast";

        Console.WriteLine($"{role} ({nationality})");
        Console.WriteLine($"Languages: {string.Join(", ", langs)}");
    }

    // ⚙️ Skills
    public static void Skills()
    {
        var skills = new Dictionary<string, string[]>
        {
            ["GameDev"] = new [] { "Unity", "C#", "Code Architecture" },
            ["Programming"] = new [] { "C++", "Python", "JS", "TSX", "Java" },
            ["Tools"] = new [] { "Git", "VSCode", "Blender" },
            ["Systems"] = new [] { "Windows", "Linux", "Networking" }
        };

        foreach (var cat in skills)
        {
            Console.WriteLine($"[{cat.Key}] => {string.Join(", ", cat.Value)}");
        }
    }

    // 💬 Extra Info
    public static void Status()
    {
        Console.WriteLine("🔭 Currently working on a strategy video game");
        Console.WriteLine("🌱 Learning Git and Code Architecture");
        Console.WriteLine("💬 Languages: Spanish, Catalan, English");
        Console.WriteLine("😄 Pronouns: she/her");
        Console.WriteLine("⚡ Fun fact: my cute little cat is cross-eyed");
    }
}

public class Program
{
    public static void Main()
    {
        Daniella.Contact();
        Daniella.About();
        Daniella.Skills();
        Daniella.Status();
    }
}

---

### 🧩 Skill icons

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=unity,cs,cpp,python,js,git,linux,windows,vscode,blender,photoshop)](https://skillicons.dev)

</div>
