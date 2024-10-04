```python3
class Attributes():
	@staticmethod
	def knowledge() -> tuple:
		platforms = {
			'good': 	['Linux'],
			'medium': 	['Windows'],
			'basic':	['Android', 'iOS']
		}
		langs = {
			'medium':   	['Python3', 'C'],
			'low': 		['JS', 'PHP', 'SQL', 'Java'],
			'learning': 	['Ruby', 'ASM']
		}
		frameworks = 		['Yii2', 'Flask', 'Spring']
		tools = 		['VScode', 'Docker', 'Ghidra', 'Frida', 'Jeb', 'Mitmproxy', 'Burp Suite']

		return platforms, langs, frameworks, tools
	
	@staticmethod
	def skills() -> tuple:
		specialties  = ['Security engineer', 'Reverse engineer', 'Pentester']

		return specialties
```
