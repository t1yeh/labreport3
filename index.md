2. ##
```$ grep -v '[a-zA-z]' biomed/*.txt | head -10```
```$ grep -r -v 'police' 911report/*.txt | head -10```


```$ grep -A 2 "police" 911report/*.txt | head -5```
```$ grep -A 1 "CIA" 911report/*.txt | head -5```


```$ grep -E "Flight [0-9]{2}" 911report/*.txt | head -5```
```$ grep -E "([A-Z][a-z]{2,})-[0-9]{3,}" biomed/*.txt | head -5```

```$ grep -r -hc "CIA" government | sum```
```$ grep -hc "3-2" biomed/*.txt | sum```
