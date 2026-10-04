
## Strong vs Weak References 

### Reference 
 Reference is basically anything that holds the memory address of an object. 
### Strong Reference
A strong reference is an object that is alive as long as the reference to it exists. Android keeps the strong 
reference around as long as the reference to the object exists. In android, if a long-lived objects holds an activity context,
it can accidentally keep the screen and its resources alive after the screen closes. A real life example would be like holding someone's hand. 

### Weak Reference 
A weak reference is like having someone's phone number on a note that might get thrown away. It doesn't keep the object alive. Android may clean it up.
You must check if the object exists or not before you use it. 


