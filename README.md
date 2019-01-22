# Projects 
// PolishNotation_RadixSort is a project with two main parts: 
1: Application for calculating complex arithmetic expressions (containing parantheses, and any operand, including powers)
  a: First step is to transform the expression in the Polish Notation (which has no parantheses);
  b: Second step is to evaluate this Polish Notation and get to the final result;
2: Radix Sort Algorithm, used for sorting numbers; it uses 10 queues (one for each digit) and uses them to sort the numbers step-by-step, starting from the least significant digit, until the most significant one.

// Another project is an app for creating, storing and distributing different types of surprises:
1. Candy, FortuneCookie and MinionToy are the classes used to create the surprise objects.
2. FIFOBag, LIFOBag and RandomBag are classes that define the container objects, with queue, stack and random behavior. They all implement the IBag interface, so they override the same methods. This also makes the app scalable, for the possibility of creating new bags at a later time.
3. GatherSurprises is used to generate the candies (delegating this to the constructors).
4. BagFactory is used to create any of the different types of containers.
5. AbstractGiveSurprises, extended by 3 other classes (GiveSurpriseAnd...) is responsible of putting the generated surprises into bags and then distributing them, having the possibility of setting a waining time between the releases.
6. Test class comprises a comprehensive example of use of this app, by testing all of its features.
