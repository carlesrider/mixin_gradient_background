# Gradient Background Mixin SCSS
Vertical, horizontal and diagonal gradient backgrounds mixin

* [Vertical Gradient](#vertical)
* [Horizontal Gradient](#horizontal)
* [Diagonal Gradient](#diagonal)

---
## <a name="vertical"></a>Vertical Gradient

### Description
*Mixin to easy create vertical gradient, from top to bottom*
### Parameters
* ```$from``` - variable that define the start color of gradient
* ```$to``` - variable that define the end color of gradient 
### Usage
Just include the mixin to the selector. For exemple for a vertical gradient from white to black:
```scss
.exampleGradient {
    @include vertical-gradient(#ffffff,#000000);
}
```

---
## <a name="horizontal"></a>Horizontal Gradient

### Description
*Mixin to easy create horizontal gradient, from left to right*
### Parameters
* ```$from``` - variable that define the start color of gradient
* ```$to``` - variable that define the end color of gradient 
* ```$stop``` - variable that define when to stop the end color ```$to``` (__default: 100%__)
### Usage
Just include the mixin to the selector. For exemple for a horizontal gradient from black to white:
```scss
.exampleGradient {
    @include horizontal-gradient(#000000,#ffffff);
}
```

---
## <a name="diagonal"></a>Diagonal Gradient

### Description
*Mixin to easy create diagonal gradient, from top left to bottom right*
### Parameters
* ```$from``` - variable that define the start color of gradient
* ```$to``` - variable that define the end color of gradient 
* ```$stop``` - variable that define when to stop the end color ```$to``` (__default: 100%__)
### Usage
Just include the mixin to the selector. For exemple for a diagonal gradient from red to blue:
```scss
.exampleGradient {
    @include horizontal-gradient(red,blue);
}
```