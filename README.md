# numpyFile
import numpy as np
a=np.array([[1,1,1],[1,1,1]])
dim=int(input("enter the dimention :"))
b=np.identity(dim,dtype=int)
print(b,"\n")
print("shape of identity matrix:",b.shape)
print("dimention of identity matrix:",b.ndim)
c=a*dim
print(c,"\n")
d=np.ones_like(c)
print(d,"\n")
e=np.zeros_like(c)
print(e,"\n")
