Cockcroft Headroom Plot in R
============================

Code originally written 2006-2008, [documented on my old blog](http://perfcap.blogspot.com/2008/07/enhanced-headroom-plot-in-r.html)

Inspiration from this [CMG/HPTS paper](http://www.hpts.ws/papers/2007/Cockcroft_CMG06-utilization.pdf) "Utilization is Virtually Useless as a Metric", so what should we use instead? Bottom line: "Utilization is properly defined as busy time
as a proportion of elapsed time. The replacement for utilization is headroom which is defined as the unused proportion of the maximum useful throughput."

To use:
> source("chp.r")

To test:
> chp(1:10,1:10)
This will open a plot window showing the following image
![chptest](chptest.png)

Github repo created to celebrate #TLAPD2016 Arrrrrrr, R
![Arrrrrrr](https://pbs.twimg.com/media/CsrmI7DWAAAt176.jpg)
