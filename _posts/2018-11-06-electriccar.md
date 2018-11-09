

```python
# ElectricCar Class
class ElectricCar :
    def __init__(self,model_name):
        self.model_name = model_name
# Stop 
    def stop(self):
        # Motor stop
        print "모터를 정지합니다."

# Start 
    def start(self):
        # Motor run
        print "모터를 가동합니다."

# Run
    def run(self):
        # drive
        print "정속 운행을 합니다."

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
    electric_car_1 = ElectricCar("전기차1")
    electric_car_1.get_car_name()
    electric_car_1.stop()
    electric_car_1.start()
    electric_car_1.run()
    electric_car_1.break_pad()
    
if __name__ == '__main__':
    main()
```

    메인함수입니다.
    전기차1이(가) 달립니다.
    모터를 정지합니다.
    모터를 가동합니다.
    정속 운행을 합니다.
    브레이크를 밟습니다.
    배터리를 충전합니다.
    


```python

```
