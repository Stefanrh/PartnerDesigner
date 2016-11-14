# PartnerDesigner

Clone the C# project PartnerDesigner. 
This exercise is about discovering some problems in using the simple, built-in types like String and int, and trying to improve the code by using enumerated types instead. 
In the project, the class Human has been included. The class contains four instance fields, one for: 
* Gender 
* Eye color 
* Hair color 
* Height category 

You can thus create a Human object (your future partner…) by specifying values for each of these four properties in the class constructor. Furthermore, you can get a textual description of a Human object by calling the method GetDescription(). 
Some code that tests the Human class is as always included in InsertCodeHere.cs. 

1. Examine the code in the Human class definition and in InsertCodeHere.cs, and see if you can predict the outcome of running the program 

Running the program reveals some problems. In two cases, we have specified hair color where we should have specified eye color, and vice versa (unless you really want a partner with white eyes and blue hair…, and in one case, we have specified a non-existing height category 

2. Change the Human class definition by adding enumerated types for gender, eye color, hair color and height category. Use these new types for the four instance variables. The constructor needs some changes as well. Also consider if you still need the methods GetGenderDescription and GetHeightDescription 

3. Change the code in InsertCodeHere.cs, so it is compatible with the redesigned Human class. Observe how it is now only possible to specify legal values for each type. 

4. Reflect a bit on the changes. Is there anything in the new code that is more complicated than it was in the original code? Was it always relevant to use an enumerated type? 
