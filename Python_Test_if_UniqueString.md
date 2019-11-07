
# Check if the string has unique character

### Implement an algorithm to determine if a string has no repeating character


```python
s1 = 'Python'
s2 = 'Java'

def unique_string(oranges):
    return len(set(oranges)) == len(oranges)


print(unique_string(s1))
print(unique_string(s2))
```

    True
    False
    
