# File Handling
A common process is to collect data from files but also store data in files. Files come in a large set of different flavours/types (TXT, JSON, YAML, ...) and handling of the specific type will also be handled in this page. But lets start out with just reading and writing to a file.

## Basic Handling
### Read File

```python
file = '<file_path>'

with open(file, 'r') as fpr:
  content = fpr.read()
```

### Write File

```python
file = '<file_path>'

content = 'Hello World'

with open(file, 'w') as fpw:
  fpw.write(content)
```
