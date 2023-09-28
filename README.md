```python3
class Attributes():
	@staticmethod
	def knowledge() -> tuple:
		platforms = {
			'medium': 	['Windows', 'Linux'],
			'basic':	['Android', 'iOS']
		}
		langs = {
			'medium':   	['Python3'],
			'low': 		['JS', 'PHP', 'SQL', 'Java', 'C'],
			'learning': 	['Ruby', 'ASM']
		}
		frameworks = 		['Yii2', 'Flask', 'Spring']
		tools = 		['VScode', 'Docker', 'Ghidra', 'Frida', 'Jadx', 'Mitmproxy', 'Burp Suite']

		return platforms, langs, frameworks, tools
	
	@staticmethod
	def skills() -> tuple:
		specialties  = ['Security engineer', 'Reverse engineer', 'Pentester']

		return specialties, vulnerability_statistics
```
