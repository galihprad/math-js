# math-js
Some Math formulas written in JS

#

### Content
##### [Square](#square-1)
##### Circle
##### Triangle

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
```javascript
TriangleArea(a,b,c){
  let s = (a+b+c)/2; // semi perimeter
  let area = Math.sqrt(s*(s-a)*(s-b)*(s-c));
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
