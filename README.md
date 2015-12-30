# text-functions-library-javascript
Open-Source JavaScript Library for commonly used text functions.<br /><br />
Many of the functions are similar to Visual Basic text function syntax, which I often found more intuitive to use than native JavaScript functions.

##Setup:

Inslude text-me.js file in your project.
Ex.

```html
<script src="text-me.js"></script>
```
---
---
---

##Usage:
---
**left Function Syntax**

Returns specified number of characters from the left of a text string.

>left([Text as String],[Number of Characters])

```javascript
var mytext = "Text that we would like to use, and then more.";
left(mytext,3);
// Returns Tex

// you can also use the following syntax
mytext.left(3);
```

---

**right Function Syntax**

Returns specified number of characters from the right of a text string.

>**right([Text as String],[Number of Characters])**

```javascript
var mytext = "Text that we would like to use, and then more.";
right(mytext,4);
// Returns ore.
```


---

**mid Function Syntax**

Returns specified number of characters from the starting point defined in the middle of a text string.

>**mid([Text as String],[Starting Character],[Number of Characters])**

```javascript
var mytext = "Text that we would like to use, and then more.";
mid(mytext,6,4);
// Returns that
```


---

**midd Function Syntax**

Returns characters from from the middle of a text string using start and end character number.

>**midd([Text as String],[Start Character],[End Character])**

```javascript
var mytext = "Text that we would like to use, and then more.";
mid(mytext,11,12);
// Returns we
```
