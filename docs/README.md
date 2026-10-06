# hw-analytics

Домашняя работа по анализу данных и машинному обучению.

> [!TIP]
Содержит датасеты для домашних работ, чтобы использовать их в Google Colab

## Использование файлов из репозитория в Google Colab

```python
def get_data_from_url(url: str) -> str | None:
  import requests
  response = requests.get(url)
  if response.status_code == 200:
      data = response.text
      return data;
  else:
      print("Произошла ошибка!")
```
