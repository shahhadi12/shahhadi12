from matplotlib import pyplot as plt
import random
import pandas as pd
import numpy as np
import statistics
b=2
p=[]
for Roosters in range(1,150): 
    x = random.uniform(0, 1)
    p.append (x)
   
#Each rooster has a strategy type (hawk or dove) 
b=2
c=5
q=0.3
f=0.7
score = np.array([[((b-c)/2), b],[0, (b)/2]])
# re-label the rows and columns
jpm=pd.DataFrame(score, columns=['dove', 'hawk'])
jpm.index = ['dove', 'hawk']
#Each rooster has a strategy type (hawk or dove)
n = round(random.uniform(0, 1), 4)
stra = random.choice (p)
strb = random.choice (p)
def __init__(strb, stra):
        """
        Each  stra or strb has a strategy type (hawk or dove)
        """       
n=[]  

#create a list of play options and write the payoff function
def payoff_function (stra , strb,dove, hawk ): 
 n = random.uniform(0, 1)
 for i in range (10):
    
    if stra == 'dove ' and strb == 'dove' and stra>n and strb>b:#score=b/2
     stra=stra+((1-f)*(b/2))
     n=np.append(stra)
     strb=strb+((1-f)*(b/2))
     strb=np.append(n)
    elif stra == 'dove' and strb == 'hawk'and stra>n and strb<b: #score=0
      stra=stra+(0)
      stra.append(n)
      strb=strb+(0)
      strb.append(n) 
    elif stra == 'hawk' and strb == 'dove'and stra<n and strb>b:#score=b
      stra=stra+(f*b)
      stra.append(n)
      strb=strb+((1-q)*b)
      strb.append(n)           
    elif stra == 'hawk' and strb == 'hawk'and stra<n and strb<b:#score=(b-c)/2
      stra=stra+((f*(b-c)/2))
      stra.append(n)
      strb=strb+((q*(b-c)/2))
      strb.append(n)
      stra.sorted()
      n.reverse()
      print(n)
      average = statistics.mean(n)
      print( average)
      return payoff_function 
 #################
def h(): 
  if n <= 0.2:
 remove(n=) in range(30) from(100)
 
 h=100
def nex (p):
 for h in range(1000):
    
   for m in range(1, 70):
    m= random.uniform(0, 1)  
    x = [random.gauss(0,1) for _ in range( 1, 30)]
    m.append (x)
    x.append(n)
    n.append(p)
   payoff_function
   return nex (p)
############################






#ef check_win( win):
       
#if score_strb> 0.6 or score_strb > 0.9 :
# print('win') 
#return check_win
#h=100 
#for h in range (1000):           



  
plt.plot(p)
plt.xlabel("Roosters")
plt.ylabel("p")
plt.title("Game Theory")
plt.show()
plt.subplot(1,2,2)
y=[1,2,3,4,5,6,7,8,9,10]
#x=[average]
plt.plot(n, y)
plt.ylabel('p')
plt.xlabel('n')
#y=[1,2,3,4,5,6,7,8,9,10]
