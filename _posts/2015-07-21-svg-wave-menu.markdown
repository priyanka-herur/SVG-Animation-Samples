---
layout: post
title:  "Wavy Menu"
date:  2015-07-21 9:34:20
categories: 
author: Priyanka Herur
image: 
    feature: img/new_wave.svg
---
You can build a wave like animations using SVG for handling any user interaction. This example uses only SVG without any library.

{% highlight htmlentities %}
 <animate  dur="1s" id="animatemypath"
            repeatCount="1" 
            attributeName="d" 
            keyTimes="0;.5;1"
            keySplines=".42,0,.6,1; 0,0,0.3,0.6;"
            calcMode="spline" 
            begin="click"
            values=" ... "
           />
{% endhighlight %}

Check out [SVG animation][animation] for complete code. File all bugs/feature requests at [my GitHub repo][priyanka-gh]. If you have questions, you can leave a comment here.

[animation]:   http://priyanka-herur.github.io/SVG-Animation-Samples/wave_menu/new_wave.svg
[priyanka-gh]:  https://github.com/priyanka-herur/