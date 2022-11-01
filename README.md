A value type saves the actrul value in the variable while a refrence type saves a reference to a value

A value type contains a unique copy of data and a reference type could share data between variables.

Value type could be mutable if decleard by var and immutable if decleared with let. 
While reference type is always mutable

the advantage of value type is it is safer and generaly faster, and the advantage of reference type is 
if you only need to change once when you need to change all the variable that reference to the same address

the use of value type is tuple, enum, structureand all the primary data types.
and the use of reference type is class function and closure

you can also use value type in a reference type value or use reference type in a value type
for example, a class that contain a tuple, or a tuple of classes

