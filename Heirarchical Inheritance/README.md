If more than one class is inherited from the base class, it's known as hierarchical inheritance.
 In hierarchical inheritance, all features that are common in child classes are included in the base class.


For example, Physics, Chemistry, Biology are derived from Science class. Similarly, Dog, Cat, Horse are derived from Animal class.
Syntax of Hierarchical Inheritance

class base_class {
     ... .. ...
}

class first_derived_class: public base_class {
     ... .. ...
}

class second_derived_class: public base_class {
     ... .. ...
}

class third_derived_class: public base_class {
     ... .. ...
}
