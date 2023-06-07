```python3
class Attributes():
	@staticmethod
	def coding() -> tuple:
		langs = {
			'expert':   ['Python3'],
			'intermediate': ['JS', 'PHP', 'SQL'],
			'learning': ['Java', 'Ruby']
		}
		frameworks = ['Yii2', 'Flask', 'Nuxt.js']
		environnement = ['VScode', 'Android Studio', 'Docker']
		
		return langs, frameworks, environnement
	
	@staticmethod
	def skills() -> tuple:
		specialties  = ['Security engineer', 'Web/App reverse engineering', 'Fullstack']
		vulnerability_statistics = {
			'SQLi': 4,
			'RCE': 0,
			'XSS': 6,
			'IDOR': 5,
			'CSRF': 2
		}
		zero_days = 0
		
		return specialties, vulnerability_statistics, zero_days
```
