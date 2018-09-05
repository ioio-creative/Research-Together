# Research-Topics
## 2. p5.js
* online editor [https://editor.p5js.org/]

## 1. Payroll
* JSPDF [https://rawgit.com/MrRio/jsPDF/master/]

### Get the current date in JavaScript?
https://stackoverflow.com/questions/1531093/how-do-i-get-the-current-date-in-javascript

### Sample
* ![alt text](https://github.com/ioio-creative/Research-Together/blob/master/reference/Payroll%20Example.jpg)

# Basic Tutorials

### Do A For-Loop [https://www.w3schools.com/js/js_loop_for.asp]
```
var cars = ["BMW", "Volvo", "Saab", "Ford", "Fiat", "Audi"]; //This is an array
var text = "";

Instead of writing:
    text += cars[0] + "<br>";  // "<br>" is Nextline in HTML
    text += cars[1] + "<br>"; 
    text += cars[2] + "<br>"; 
    text += cars[3] + "<br>"; 
    text += cars[4] + "<br>"; 
    text += cars[5] + "<br>";

You can write:
    var i;
    for (var i = 0; i < cars.length; i++) { 
    text += cars[i] + "<br>";
    }


Result:
    BMW
    Volvo
    Saab
    Ford
    Fiat
    Audi
```

### What is a JSON File? [https://www.w3schools.com/js/js_json.asp]
```
object
{}

array
[]

string
"text"

numbers
123

format example:
{                                                   //object
"employees":                                        //key : value ->Key is a string, value is an array
    [                                               //array (with 3 object)
        {"firstName":"John", "lastName":"Doe"},     //comma is necessary for separating the items
        {"firstName":"Anna", "lastName":"Smith"},   //key : value (usually in pair)
        {"firstName":"Peter", "lastName":"Jones"}
    ]
}

```


