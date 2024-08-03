# Mapreduce-Example-word-count

# step 1
```bash
cat input.txt | python mapper.py
```
# step 2 

```bash
cat input.txt | python mapper.py |sort | python reducer.py
```
