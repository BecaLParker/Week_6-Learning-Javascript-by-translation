https://hackmd.io/kMNgXiPHQf2Q_P9A-tnS9A

1. Make a list of all the bits of Ruby you can think of.  
2. Sort the list in order of importance. Don’t think about it too much, just whatever feels most important to you to learn. You can always re-order it.  
3. Starting at the top of the list, learn how to do each thing in Javascript.  

# Things I've found translations for
### Variables
You declare a JavaScript variable with the `var` keyword: `var carName;` After the declaration, the variable has no value (technically it has the value of undefined).  Assigning a class object to a variable: `var dog = new Dog();`

### Assignment operators
Hooray! these look to be the same as Ruby ( `= , += , -= , *= `)

### Maths (Addition etc) 
Same as ruby?

### Arrays
Same as ruby  

### Boolean logic operators 
Almost the same as ruby, but notably `==` in JS means equal to, vs. `===` meaning equal value and equal type. Seems like most situations will call for triple equal. 

### [Classes](https://github.com/makersacademy/course/blob/master/pills/js_classes.md)
`class Dog {}`

### [Methods](https://github.com/makersacademy/course/blob/master/pills/js_classes.md#defining-methods)
Within a class you can do:
```
someMethodName(some Parameter) {
  // code you want the method to run on the class object. Don't forget a `;`
}
```
[standalone functions and arrow function syntax](https://github.com/makersacademy/course/blob/master/thermostat_es6/walkthroughs/javascript_basics.md) are also a thing.


### [Instance variables](https://github.com/makersacademy/course/blob/master/pills/js_classes.md#initialisation-code)
`this.breed = breed;` ?

### [Initialize](https://github.com/makersacademy/course/blob/master/pills/js_classes.md#initialisation-code)
In JavaScript, the `constructor` method is called.

```
class Dog {
  constructor(breed) {
    this.breed = breed;
  }
}
```

### [attr_readers / accessors](https://github.com/makersacademy/course/blob/master/pills/js_classes.md#initialisation-code)
In javascript, there are no attr_reader or attr_accessor. Instead, instance variables are accessible to the outside via dot-notation.
 
### running in irb / load ruby
`open SpecRunner.html`
In the same browser window where your SpecRunner.html is loaded up, open your console (Google Chrome shortcut is cmd + option + i) and at the prompt initialise an instance of your class to get going eg `var javabuzz = new Javabuzz();`

### Output functions (return/puts/print/p):
```console.log(`${thing} to print`)```.  Don't forget to use back-ticks for strings that will contain interpolation (`${}`).  

### Still to learn
- Hashes
- If statements  
- Switch statements  
- each loops  
- while loops  
- raise error if..   
- Input functions (gets.chomp / method parameters)  
- Dependency injection  
- Constants  
- spec expect to eq  
- rspec expect to change  
- require file  
- gems  


