# factorial-digit-sum

from math import factorial
import time
start = time.time()
a = list(str(factorial(100)))
a = [int(x) for x in a]
fds = sum(a)
end = time.time()
print ('Found {} in {} seconds'.format(fds,end-start))
