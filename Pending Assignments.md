```python
t = int(input())

for i in range(0, t):
    x, y, z = map(int, input().split())
    if((x*y) > (z*24*60)):
        print("NO")
    else:
        print("YES")

```
