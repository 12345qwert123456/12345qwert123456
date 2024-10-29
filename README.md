```python3
class Attributes():
    @staticmethod
    def knowledge() -> tuple:
        platforms = {
            'good':    ['Linux'],
            'medium':  ['Windows'],
            'basic':   ['Android', 'iOS']
        }
        langs = {
            'medium':   ['Python3', 'C'],
            'reading':  ['JS', 'PHP', 'SQL', 'Java'],
            'learning': ['Ruby', 'ASM']
        }
        frameworks = ['Yii2', 'Flask', 'Spring']
        tools =      ['Docker', 'Ghidra', 'Frida', 'Jeb', 'Burp Suite']

        return platforms, langs, frameworks, tools
    
    @staticmethod
    def skills() -> tuple:
        specialties  = ['Security engineer', 'Reverse engineer', 'Pentester']
        education =    ['Bachelor`s degree - Information Security']

        return specialties, education
```
