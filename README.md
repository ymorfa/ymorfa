<div align="center">
   <img width=100% src=https://capsule-render.vercel.app/api?type=waving&height=100&color=gradient&reversal=true />
</div>

<h3 align="center">
  Hi there 👋, I'm Yamil
</h3>

<p align="center">
  <a href="https://git.io/typing-svg">
    <!-- left padding via transparent spacer -->
    <img src="https://readme-typing-svg.demolab.com/?lines=Data+Scientist;ML%2FAI+Expert;Feel+free+to+look+around+%F0%9F%91%80;Let%27s+build+something+cool;Open+to+collaboration+%F0%9F%A4%9D&center=true&width=440&height=45"
         alt="Typing SVG" />
  </a>
</p>

```python
from dataclasses import dataclass

@dataclass(frozen=True)
class YamilMorfa:
    name: str = "Yamil Ernesto Morfa"
    role: str = "Data Scientist & Statistician"
    location: str = "Mexico City, MX"
    stack: tuple = ("Python", "SQL", "PySpark", "Azure")
    objective: str = "turn data into decisions"

    def build(self) -> str:
        return f"{self.name} ✅ | {self.role} | {self.location}"


def discovery(me: YamilMorfa):
    return {"me": me, "problem": me.objective, "constraints": ["quality", "impact", "reproducibility"]}

def feature_engineering(ctx):
    me = ctx["me"]
    ctx["signals"] = ["ML/AI", "Applied Statistics", "End-to-end delivery"]
    ctx["features"] = list(me.stack) + ctx["signals"]
    return ctx

def deploy(ctx):
    me = ctx["me"]
    return (
        f"{me.build()}\n"
        f"artifact: {ctx['problem']} 🚀\n"
        f"features: {', '.join(ctx['features'])}\n"
        f"status: 👀 feel free to look around — PRs welcome 🤝"
    )

if __name__ == "__main__":
    me = YamilMorfa()
    print(deploy(feature_engineering(discovery(me))))
```

## &nbsp;Tech Stack
### Languages
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,r" />
  </a>
</p>

### Frameworks & Libraries
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=fastapi,django,pytorch,tensorflow,sklearn,opencv" />
  </a>
</p>

### Databases
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb" />
  </a>
</p>

### Tools & DevOps
<p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=git,github,docker,kubernetes,vscode,linux" />
  </a>
</p>

## GitHub Stats

<div align="center">

  <p align="center">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=ymorfa&theme=dark&hide_border=true" alt="GitHub Streak" />
    &nbsp;&nbsp;
  </p>
</div>

---
## Connect With Me
<p align="center">
  <a href="mailto:morfayamil@gmail.com"><img src="https://skillicons.dev/icons?i=gmail"></a> 
  <a href="https://www.linkedin.com/in/yamil-morfa"><img src="https://skillicons.dev/icons?i=linkedin"></a>
</p>
