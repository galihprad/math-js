# math-js
Some Math formulas written in JS


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

##### Perimeter
```javascript
TrianglePerimeter(a,b,c){
  let perimeter = a+b+c;
  return perimeter;
}
```
