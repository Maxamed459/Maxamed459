<pre>
  __  __                                                 _     __  __           _           _   _ 
 |  \/  |                                               | |   |  \/  |         | |         | | (_)
 | \  / |   __ _  __  __   __ _   _ __ ___     ___    __| |   | \  / |   __ _  | |__     __| |  _ 
 | |\/| |  / _` | \ \/ /  / _` | | '_ ` _ \   / _ \  / _` |   | |\/| |  / _` | | '_ \   / _` | | |
 | |  | | | (_| |  >  <  | (_| | | | | | | | |  __/ | (_| |   | |  | | | (_| | | | | | | (_| | | |
 |_|  |_|  \__,_| /_/\_\  \__,_| |_| |_| |_|  \___|  \__,_|   |_|  |_|  \__,_| |_| |_|  \__,_| |_|
</pre>
                                                                                                  


```python
class SoftwareEngineer:
    def __init__(self, name, role, niche, languages, tech_stack, skills, contact):
        self.name = name
        self.role = role
        self.niche = niche
        self.languages = languages
        self.tech_stack = tech_stack
        self.skills = skills
        self.contact = contact

    def introduce(self):
        return (
            f"{self.name} | {self.role} ({self.niche})\n"
            f"Languages: {', '.join(self.languages)}\n"
            f"Tech Stack: {' · '.join(self.tech_stack)}\n"
            f"Skills: {', '.join(self.skills)}\n"
            f"Contact: {self.contact}"
        )


me = SoftwareEngineer(
    name="Maxamed Mahdi",
    role="Software Engineer",
    niche="Backend Engineering",
    languages=["Somali", "Arabic", "English"],
    tech_stack=[
        "Node.js", "Python", "Django", "DRF",
        "TypeScript", "React", "Next.js", "Flutter"
    ],
    skills=["Web application development", "Mobile app development"],
    contact="maxamedmahdi459@gmail.com"
)

print(me.introduce())
