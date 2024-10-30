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
            'medium':   ['Python3', 'C++'],
            'reading':  ['JS', 'PHP', 'SQL', 'Java', 'C#'],
            'learning': ['Ruby', 'ASM']
        }
        tools =      ['Docker', 'Ghidra', 'Frida', 'Jeb', 'Burp Suite']

        return platforms, langs, tools
    
    @staticmethod
    def info() -> tuple:
        specialties  = ['Security engineer', 'Reverse engineer', 'Pentester']
        education =    ['Bachelor`s degree - Information Security']
        links = {
            'HTB':      'https://app.hackthebox.com/profile/1667605',
            'Github':   'https://github.com/12345qwert123456',
            'Habr':     'https://career.habr.com/12345qwert123456'
        }
        return specialties, education, links
```
