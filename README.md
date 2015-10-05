#Bubble Animation (using JavaScript)

The bubbles in the string scatter about and regroup when the mouse is moved over it.



###How to incorporate in your web page ?

The `main.js` file includes the animation script. The animation is based on external script files. 

The external files used are as:
- [jquery.js](//code.jquery.com/jquery-1.10.2.min.js)
- [alphabet.js](http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/alphabet.js)
- [bubbles.js](http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/bubbles.js)

It can be incorporated in `<html>` by placing the following the lines in the `<head>`:


```
<script 
  type="text/javascript" 
  src="//code.jquery.com/jquery-1.10.2.min.js">
</script>

<script 
  type="text/javascript" 
  src="http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/bubbles.js">
</script>

<script 
  type="text/javascript" 
  src="http://s3.amazonaws.com/codecademy-content/courses/hour-of-code/js/alphabet.js">
</script>
```


and the following in the `<body>`:

```
<script 
  type="text/javascript" 
  src="main.js">
</script>
```



###Sample
![](https://github.com/jig08/Bubble-Animation/blob/master/sample/i1.png)
![](https://github.com/jig08/Bubble-Animation/blob/master/sample/i2.png)
![](https://github.com/jig08/Bubble-Animation/blob/master/sample/i3.png)
![](https://github.com/jig08/Bubble-Animation/blob/master/sample/i4.png)


***
***
Gratias: [codecademy](https://www.codecademy.com), [Google](http://www.google.com/logos/particle.html), [Rob Hawkes](https://github.com/robhawkes/google-bouncing-balls) and [Mark Brenig-Jones & Emile Petrone](http://dotty-dots.appspot.com/)
