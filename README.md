# draw-neural-network
Quick tool to draw fully connected neural network architectures


USAGE: <br>
 GET:<br>
  BASE URL = `http://nlp.motherbot.co:8093/plot` <br>
  PARAMS  = `nodes=2&nodes=5&nodes=10`
  
  
Use the base url and append the values with param name as *nodes* . Each param represents the layers and its value represents the number of nodes in that layer.

Some of the results:
URL = http://nlp.motherbot.co:8093/plot?nodes=1&nodes=2
![2 layer](1524090412.png)

URL = http://nlp.motherbot.co:8093/plot?nodes=3&nodes=4&nodes=5&nodes=6
![4 layer](1524090373.png)


URL = http://nlp.motherbot.co:8093/plot?nodes=1&nodes=10&nodes=10&nodes=1
![4 layer with multiple nodes](1524092372.png)

