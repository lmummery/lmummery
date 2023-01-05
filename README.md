<h1><img src="foxicon.png" height="26pt" style="margin-right: 15px">      luke mummery.</h1>

```python
class About(Me):
	def __init__(self) -> None:
		self.name = "Luke Mummery"
		self.pronouns = "they / them"

	def getWork(self) -> list[dict]:
		return [
			{
				"company": "Jam Coding Medway",
				"position": "Code Coach"
			},
			{
				"company": "Goldsmiths, University of London",
				"position": ["Student", "Teaching Assistant"]
			}
		]
	
	def getQualifications(self) -> list[dict]:
		return [
			{
				"title": "BSc (Hons) Computer Science",
				"university": "Goldsmiths, University of London",
				"graduating": 2023
			},
			{
				"title": "Post-Graduate Certificate in Education",
				"university": "Leeds Beckett University",
				"graduating": 2024
			}
		]
	
	def getKnowledge(self) -> list[str]:
		return [
			"Python",
			"JavaScript",
			"Java",
			"C#",
			"HTML",
			"Pug",
			"CSS",
			"SASS",
			"SQL"
		]
	
	def getGoal(self) -> str:
		return "To bring more Computing to the classroom"
```

<!---
lmummery/lmummery is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
