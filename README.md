# Basic knowledge
## python
1.Containers\
dictionary{list can not be key}\
 dict.clear():only clear the value, although can't print, we still can use ''=xx  to add value \
 dict.get('','N/A'): when you not sure whether the key exist or not, get will return value(exist) or N/A(not exist)\
 dict.has_key(key): return True or False\
 dict.setdefault(): if not exist,it will add into dict\
 dict.keys() dict.values() dict.items(): if need to print with format one by one, need loop\
 dict.copy(): opposite dirction,not change fitst level value if changing original dict( dict1=dict2 will be the same after change dict2)\
 dict.fromkeys(seq[, value]):keys are items in seq,values are 'value'\
 dict.update(dict2):add or change\
 cmp(dict1,dict2):compare,return 1 or -1\
list[]\
  list.append()\
set{only distinct element,unordered}\
  set.add()\
  print:\
    for index,item in enumerate(set)：print(index，item） not error but not as what you expect\
    Set comprehensions: print({int(sqrt(x)) for x in range(5)})\
tuple(immutable)\
  not support item assignment,only can change tuples in a list\
2.file\
  read file: with open(file,'r') as f: content = f.read(). ... **or** for line in f.readlines(): ... If need, check f.readabel() first\
  r+: read and write\
  file length:\
    count = len(open(filepath, 'r').readlines()) **or** count = 0; for index, line in enumerate(open(filepath,'r'))：count += 1;\
3.web\
  HTTPServer(('', port), MyHTTPRequestHandler)


## Javascript
Rapheal

## Audio Plugin Development
use juce API and C++ \
Observer pattern, \
DSP: circular buffer(bufferSize=sampleRate*maxDelayTime) for left and right channel and free the memory in destructor(nullprt); feedback*scalar to make it quieter\
need interpolation,smooth read,and make sure clear memory at the beginning
