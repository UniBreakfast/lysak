### Скільки секунд у 42 хвилинах і 42 секундах?
```python
seconds = 42 * 60 + 42
print("In 42 minutes and 42 seconds: ", seconds, "seconds")
# In 42 minutes and 42 seconds:  2562 seconds
```

### Скільки миль в 10 кілометрах? (одна миля дорівнює 1,61 км.)
```python
miles = 10 / 1.61
print("In 10 km: ", miles , "miles")
# In 10 km:  6.211180124223602 miles
```

### Якщо ви пробігли 10 кілометрів за 42 хвилини 42 секунди, який ваш середній темп бігу (час, витрачений на подолання милі, в хвилинах і секундах)? Яка ваша середня швидкість в милях на годину?
```python
time_minutes_per_mile = (seconds / 60) / miles
time_seconds_per_mile = seconds / miles

print("Everage running pace in minutes :", time_minutes_per_mile, "minutes/mile")
# Average running pace in minutes : 6.874700000000002 minutes/mile
print("Everage running pace in seconds :", time_seconds_per_mile, "seconds/mile")
# Average running pace in seconds : 412.482 seconds/mile
```


