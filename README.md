# Quick tool to draw fully connected neural network architectures
<a href="https://www.producthunt.com/posts/plotneurons?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-plotneurons" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=136034&theme=light" alt="PlotNeurons - The most simple neural network plotter | Product Hunt Embed" style="width: 250px; height: 54px;" width="250px" height="54px" /></a>


## USAGE: <br>

  BASE URL = `http://xyz.com:8093/plot` <br>
  PARAMS  = `nodes=2&nodes=5&nodes=10`
  
<a href="https://tracking.gitads.io/?repo=draw-neural-network/"> Check out<img src="https://images.gitads.io/draw-neural-network/" alt=“GitAds”/> </a>  
Use the base url and append the values with param name as *nodes* . Each param represents the layers and its value represents the number of nodes in that layer.

For example here are some of the results:

URL = http://xyz.com:8093/plot?nodes=1&nodes=2
![2 layer](1524090412.png)

URL = http://xyz.com:8093/plot?nodes=3&nodes=4&nodes=5&nodes=6
![4 layer](1524090373.png)


URL = http://xyz.com:8093/plot?nodes=1&nodes=10&nodes=10&nodes=1
![4 layer with multiple nodes](1524092372.png)

Hope this will help.
<a href="https://tracking.gitads.io/?repo=draw-neural-network/"> Check out<img src="https://images.gitads.io/draw-neural-network/" alt=“GitAds”/> </a>
