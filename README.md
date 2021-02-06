# everything-I-learned
## python
1.file\
  read file: with open(file,'r') as f: content = f.read()\
  file length:\
    count = len(open(filepath, 'r').readlines()) \
    **or** count = 0; for index, line in enumerate(open(filepath,'r'))：count += 1;\  
2.dictionary\
 dict.clear():only clear the value, although can't print, we still can use ''=xx  to add value \
 dict.get('','N/A'): when you not sure whether the key exist or not, get will return value(exist) or N/A(not exist)\
3.web\
  HTTPServer(('', port), MyHTTPRequestHandler)


## Javascript
Rapheal

## Audio Plugin Development
use juce API and C++ \
Observer pattern, \
DSP: circular buffer(bufferSize=sampleRate*maxDelayTime) for left and right channel and free the memory in destructor(nullprt); feedback*scalar to make it quieter\
need interpolation,smooth read,and make sure clear memory at the beginning
