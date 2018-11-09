

```python
# 간단한 계산기

print "Multiple Calculator"
num1 = raw_input("Input 1: ")
num2 = raw_input("Input 2: ")

print int(num1)*int(num2)

```

    Multiple Calculator
    Input 1: 5
    Input 2: 6
    30
    


```python
# 함수가 실행되면 리턴값이 존재하므로 결과값을 사용할 수 있다.
def mul(val1, val2):
    return int(val1)*int(val2)
# 함수 내부에서 계산이 끝나기 때문에 결과값을 사용할 수 없다.
def mul2(val1, val2):
    print int(val1)*int(val2)

num3 = mul(5,10)  
print mul(num3, 15)

mul2(5,10)
```

    750
    50
    
