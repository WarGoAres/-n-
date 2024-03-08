# -n-
求n階層(史特靈公式)(記住結論演算法直接拿來用別再證明了)
import  math


for i  in  range(1,6):
    
    i=(2*i*math.pi)**(1/2)*(i/math.e)**i
    
print(i)    

