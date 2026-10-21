<!--
  ESTILO: Terminal / código ("script de conciliación")
  INSPIRACIÓN: Thai Braga (github.com/Thaiane/Thaiane, "Code Mode 👨🏽‍💻"), que presenta su perfil como un objeto,
  y la herramienta "Github Readme Insight Terminal Ascii" de la sección Tools de la lista.
  Lección tomada: el código debe parecer un script real de tu oficio, no una plantilla de "about me".
-->

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2200&pause=900&color=7FC8A9&vCenter=true&width=640&height=40&lines=%24+python+conciliar.py+--cliente+jeff;Reconciling+accounts...+ok;Freight+invoices+matched+to+TMS...+ok;Payroll+hours+loaded+from+Excel...+ok" alt="$ python conciliar.py --cliente jeff" />

```python
# conciliar.py
from dataclasses import dataclass, field


@dataclass
class Consultant:
    name: str = "Jeff Hernández"
    city: str = "Bucaramanga, Colombia"
    speaks: tuple = ("es", "en")
    role: str = "Accounting & financial consultant for Colombian companies"
    automates: dict = field(default_factory=lambda: {
        "freight": "Python scripts that sync freight operations with the TMS",
        "payroll": "Excel system for payroll",
        "hours":   "Excel system for time tracking",
    })
    building: str = "POS and QR ordering platform for restaurants"
    stack: tuple = ("Python", "Excel", "TypeScript", "Next.js", "Supabase")  # [COMPLETAR]
    contact: dict = field(default_factory=lambda: {
        "email": "[COMPLETAR-correo]",
        "linkedin": "[COMPLETAR-URL-LinkedIn]",
    })

    def rule(self) -> str:
        # Si se repite, se automatiza.
        return "If it repeats, automate it."


if __name__ == "__main__":
    print(Consultant().rule())
```

```console
$ ls stack/
```

<img src="https://skillicons.dev/icons?i=py,ts,nextjs,supabase,postgres,linux,git,vscode&theme=dark" alt="Python, TypeScript, Next.js, Supabase, PostgreSQL, Linux, Git, VS Code" />

```console
$ gh contributions --user sneeider11
```

<img src="https://github-readme-insight-terminal-asci.vercel.app/svg?user=sneeider11&theme=ubuntu&scale=0.6" width="100%" alt="Contribution graph in a terminal" />
