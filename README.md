from transformers import pipeline

sentiment = pipeline("sentiment-analysis")

text = "Today I felt tired but managed to finish some tasks."
result = sentiment(text)
print(result)
