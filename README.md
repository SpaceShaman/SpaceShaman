# Hello, Earthlings 🧑‍🚀

```python
class SpaceShaman(FullStackDeveloper):
    """Milky Way resident. Prefer backend, loves clean code and new tech."""

    native_language = "Python"
    main_stack = [
        "Django", "Django Ninja", "FastAPI", "Pydantic", "Celery",
        "Transformers", "Marvin", "Pytest", "Factory Boy",
        "Docker", "Docker Compose", "SQLite", "PostgreSQL",
        "TypeScript", "Nuxt.js", "Tailwind CSS", "daisyUI", "Vuetify"
    ]
    methodologies = ["TDD", "DDD"]
    code_style = ["black", "ruff"]
    docs_style = "Material for MkDocs"

    def __init__(self):
        self.galaxy = "Milky Way"
        self.role = "Full Stack Developer"
        self.focus = "Backend > Frontend"
        self.is_up_to_date = True

    def design_system(self):
        return "Loves exploring system architecture: simple, clear and scalable solutions."

    def loves(self, thing):
        return thing in self.methodologies or thing in self.main_stack

    def build_ui(self):
        return "Likes Nuxt, sometimes styles with Tailwind/daisyUI/Vuetify."

    def test_code(self):
        return "Testing with Pytest, TDD in blood."

    def lint_code(self):
        return "Linting with ruff, formatting with black."

    def update_skills(self):
        self.is_up_to_date = True

    def __str__(self):
        return (
            f"👋 Hi, I'm SpaceShaman – "
            f"full stack dev, backend-first, Python-native, "
            f"interested in IT architecture as a whole, "
            f"I believe that simple is better than complex 🧘"
        )


if __name__ == "__main__":
    me = SpaceShaman()
    print(me)
```
