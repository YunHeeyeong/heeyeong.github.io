

```python
# HybridCar Class
class HybridCar :
    def __init__(self,model_name):
        self.model_name = model_name
# Stop 
    def stop(self):
        # Engine stop
        print "엔진을 정지합니다."

# Start 
    def start(self):
        # Engine run
        print "엔진을 실행합니다."

# Assist 가속시 힘이 필요한 구간에서는 전기모터가 엔진을 보조
    def assist(self):
        print "모터를 구동합니다."

# Run
    def run(self):
        # drive
        print "정속 운행을 합니다."

# Runfast 
    def runfast(self):
        #drive
        print "가속합니다."
# Break
    def break_pad(self):
        # break
        print "브레이크를 밟습니다."
        # batteryCharge
        print "배터리를 충전합니다."

#Get Car name
    def get_car_name(self):
        print self.model_name + "이(가) 달립니다."
        

def main():
    print "메인함수입니다."
    hybrid_car_1 = HybridCar("하이브리드차1")
    hybrid_car_1.get_car_name()
    hybrid_car_1.start()
    hybrid_car_1.run()
    hybrid_car_1.runfast()
    hybrid_car_1.assist()
    hybrid_car_1.break_pad()
    hybrid_car_1.stop()
    
if __name__ == '__main__':
    main()
```

    메인함수입니다.
    하이브리드차1이(가) 달립니다.
    엔진을 실행합니다.
    정속 운행을 합니다.
    가속합니다.
    모터를 구동합니다.
    브레이크를 밟습니다.
    배터리를 충전합니다.
    엔진을 정지합니다.
    


```python

```
