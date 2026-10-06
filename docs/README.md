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

В параметр `url` нужно вставить ссылку на сырой файл датасета.

### 01-batman

```url
https://raw.githubusercontent.com/sanbob-vault/hw-analytics/refs/heads/main/01-batman/data/buildings.dat
```

### 02-medieval

```url
https://raw.githubusercontent.com/sanbob-vault/hw-analytics/refs/heads/main/02-medieval/data/ivaniv.dat
```

### 03-clustering

```url
https://raw.githubusercontent.com/sanbob-vault/hw-analytics/refs/heads/main/03-clustering/data/{НАЗВАНИЕ_ФАЙЛА}
```

#### Файлы

`20230328-Aeronsillo`
`20230328-alDhafra`
`20230328-Alpena`
`20230328-AscensionIsl`
`20230328-Athens`
`20230328-Belem`
`20230328-Boulder`
`20230328-Cachoeira`
`20230328-Chilton`
`20230328-Durbes`
`20230328-Eaglin`
`20230328-Eareckson`
`20230328-Eielson`
`20230328-Fairford`
`20230328-Fortaleza`
`20230328-Gakona`
`20230328-GRahamstown`
`20230328-Guam`
`20230328-Idaho`
`20230328-Inl`
`20230328-Jeju`
`20230328-Julisruh`
`20230328-LuaLuaLei`
`20230328-Millstone`
`20230328-Nicosia`
`20230328-Pruhonice`
`20230328-PtAruello`
`20230328-SantaMaria`
`20230328-SanVito`
`20230328-Sapron`
`20230328-Thule`
`20230328-Tromso`
`20230328-Wallops`
`20240628-Alpena`
`20240628-Ascension`
`20240628-Athens`
`20240628-Austin`
`20240628-Awase`
`20240628-Cachoeira`
`20240628-Durbes`
`20240628-Eareckson`
`20240628-Eglin`
`20240628-Eielson`
`20240628-ElArenosillo`
`20240628-Fairford`
`20240628-Gackona`
`20240628-iCheon`
`20240628-Jeju`
`20240628-Julisruh`
`20240628-Lajes`
`20240628-LuaLuaLei`
`20240628-MillstoneHill`
`20240628-PokerFlat`
`20240628-Pruhonice`
`20240628-Roquets`
`20240628-SanVito`
`20240628-Sopron`
`20240628-Thule`
`20240628-Tromso`
`20240628-Wake`
