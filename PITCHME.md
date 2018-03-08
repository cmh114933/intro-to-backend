# Intro to Ruby
---
### Key Takeaways

1. How Ruby is similar to JS
2. How Ruby is different from JS

---
### Core Principles
1. Data Types
2. Variables
3. Conditionals
4. Iteration
5. Methods
6. Enumerable
---
# Data Types
+++

What are the data types in JS?
+++
### Data Types in Ruby

```ruby
"abc" # => strings
123 # => numbers
true # => booleans
[1,2,3] # => arrays
{name: "John", age: 23} # => Hash
```
+++
### Differences from JS

1. Hash is similar to JSON
2. Arrays are actually objects in JS
3. Arrays are their own thing in Ruby
---
# Variables
+++
Javascript variable assignment
```javascript
let x = 1
var y = 2
```

+++
Ruby variable assignment
```ruby
x = 1
```


---
# Conditionals
+++
Javascript
```javascript
if(condition){
  code
} else if (condition) {
  code
} else {
  code
}
```
+++
Ruby
```ruby
if condition
  code
elsif condition
  code
else 
  code
end
```


---
# Iteration
+++

Javascript
```javascript
for( i = 0; i < 3; i++){
  console.log("I'm in the for loop")
}
```
+++
Ruby
```ruby
for i in 1..3 do
  p "I'm in the for loop"
end
```


---
# Functions/
# Methods
+++
Javascript
```javascript
sum(1,1)
function sum (x,y) {
  return x + 1
}
```
+++
Ruby
```ruby
def sum(x,y)
  x + 1
end
sum(1,1)
```

Take note of code execution flow
---
# Enumerables
+++
Javascript
```javascript
[1,2,3].forEach(function(n){
  console.log(n*2)
})
```
+++
Ruby
```ruby
[1,2,3].each do |n|
  p n * 2
end
```
The Do End Block
