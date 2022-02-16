```python
class Programmer:
    def __init__(self):
        self.name = 'Artem'
        self.company = 'Wargaming'
        self.skills = ['Python', 'Golang', 'JavaScript']
        self.databases = ['Redis', 'PostgreSQL', 'MongoDB']
        self.misc = ['Docker']
        self.working_on = ['ISTQB Certificate', 'Teaching skills']
        self.telegram = "@neverdieone"
        self.email = "altiore@mail.ru"
```


```mermaid
flowchart TD
    A[Coding] --> B{Do you like code?};
    B --> Yes --> C[Keep do it!];
    B --> No --> D[Drink some coffee];
    C --> E[Enjoy your life];
    D --> E[Enjoy your life];
```
