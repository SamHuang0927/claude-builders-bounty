# Usage Examples

## Basic Usage
```python
import module

# Initialize
client = module.Client()

# Basic operation
result = client.operation(param="value")
print(result)
```

## Advanced Usage
```python
# Advanced configuration
client = module.Client(
    timeout=30,
    retries=3,
    cache=True
)

# Batch operations
results = []
for item in items:
    result = client.process(item)
    results.append(result)
```

## Error Handling
```python
try:
    result = client.risky_operation()
except module.APIError as e:
    print(f"API Error: {e}")
except Exception as e:
    print(f"Unexpected error: {e}")
```
