# math-js 💯
Some Math formulas written in JS

#

### Content

[Square](#square)

[Circle](#circle)

[Triangle](#triangle)

[Trigonometry](trigonometry)

#

### Square

##### Area
```javascript
SquareArea(s){
  let area = s*s;
  return area;
}
```

##### Perimeter
```javascript
SquarePerimeter(s){
  let perimeter = 4*s;
  return perimeter;
}
```

### Circle

##### Area
```javascript
CircleArea(r){
  let area = Math.PI*r*r;
  return area;
}
```

##### Perimeter
```javascript
CirclePerimeter(r){
  let perimeter = 2*Math.PI*r;
  return perimeter;
}
```

### Triangle

##### Area
```javascript
TriangleArea(b,h){
  let area = b*h/2;
  return area;
}
```
```javascript
TriangleArea(a,b, angleACB){
  let area = a*b*Math.sin(angleACB)/2;
  return area;
}
```


### Trigonometry

```javascript
SinAplusB(A,B){
  let result = Math.sin(A)*Math.cos(B)+Math.sin(B)*Math.cos(A);
  return result
}
```

