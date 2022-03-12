# Football
```python
a=str(input())
count=1
ma=1
for i in range(len(a)-1):
    if a[i]==a[i+1]:
        count+=1
    else:
        count=1
    ma=max(ma,count)
if ma>6:
    print("YES")
else:
    print("NO")
```
