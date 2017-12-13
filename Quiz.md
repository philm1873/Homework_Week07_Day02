# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

"Many forms".

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

When a reference to an instance of a class has the ability to take different types.

// public class X implements Y {

// Y variable = new X() }


3. What can we use to implement polymorphism in Java?

Parent classes and interfaces.

4. How many 'forms' can an object take when using polymorphism?

Unlimited.

5. Give an example of when you could use polymorphism.

Any time you have a parent-child class relationship. The reference to the child object can take the parent's type.
This applies to classes that implement interfaces as well.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

When a class references behaviours of a group of classes.

7. When would you use composition? Provide a simple example in Java.

When you want to use methods/attributes of other classes but don't want to inherit from them.

// class X

// class Y {

}



8. What is/are the advantage(s) of using composition?

Can use behaviours from other classes without inheriting, therefore don't need to change class structure.
Allows you to reuse code.

9. What happens to the behaviours when the object composed of them is destroyed?

They are also destroyed.
