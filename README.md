```
███╗   ███╗ █████╗ ██╗  ██╗ █████╗ ███╗   ███╗███████╗██████╗     ███╗   ███╗ █████╗ ██╗  ██╗██████╗ ██╗
████╗ ████║██╔══██╗╚██╗██╔╝██╔══██╗████╗ ████║██╔════╝██╔══██╗    ████╗ ████║██╔══██╗██║  ██║██╔══██╗██║
██╔████╔██║███████║ ╚███╔╝ ███████║██╔████╔██║█████╗  ██║  ██║    ██╔████╔██║███████║███████║██║  ██║██║
██║╚██╔╝██║██╔══██║ ██╔██╗ ██╔══██║██║╚██╔╝██║██╔══╝  ██║  ██║    ██║╚██╔╝██║██╔══██║██╔══██║██║  ██║██║
██║ ╚═╝ ██║██║  ██║██╔╝ ██╗██║  ██║██║ ╚═╝ ██║███████╗██████╔╝    ██║ ╚═╝ ██║██║  ██║██║  ██║██████╔╝██║
╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚══════╝╚═════╝     ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚═╝
                                                                                                         
                                                                                                                                                            
```py
class SoftwareEngineer:
    def __init__(self, name, role, niche, speak_language, tech_stacks, skills, contact):
        self.name = name
        self.role = role
        self.niche = niche
        self.speak_language = speak_language
        self.tech_stacks = tech_stacks
        self.skills = skills
        self.contact = contact

    def introduce(self):
        print(
            f"Hi, I'm {self.name}, a {self.role} specialized in {self.niche}. "
            f"I speak {self.speak_language}. "
            f"My primary tech stack includes {self.tech_stacks}. "
            f"My skills include {self.skills}. "
            f"Get in touch: {self.contact}"
        )


me = SoftwareEngineer(
    name="Maxamed Mahdi",
    role="Software Engineer",
    niche="Backend Engineering",
    speak_language="Somali, Arabic, English",
    tech_stacks="Node.js | Python | Django | DRF | TypeScript | React | Next.js | Flutter",
    skills="Web and mobile application development",
    contact="maxamedmahdi459@gmail.com"
)

me.introduce()

