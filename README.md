1)	Explain about the different complex data types in pig.
•	Tuple:An ordered set of fields.Tuple is represented by braces.Eg:(1,2)
•	Bag:a set of tuples is called a bag.Bag is represented by flower or curly braces.Eg:{(1,2),(3,4)}
•	Map:A set of key value pairs.Map is represented in a square brackets.Eg: [Key#value]
2) How can you interact with the shell in Apache pig?
	The shell in a pig is called Grunt shell.If we want to launch this shell we can launch it by using simple command “Pig” or “pig-x local”.
	Suppose if we interact with linux terminal from pig’s grunt shell then we can use “sh” prefix followed by linux terminal commands in pig grunt shell.
3)Explain how pig differs from Map reduce?
	Pig is a high level language of expressing data analysis program which is internaly create a sequence of Map Reduce programs whereas Map is a low level of programming.
Pig is simple to learn and use as compared to map reduce.
Pig provides inbuilt optimization of Map Reduce jobs whereas in map reduce developer needs to take care of optimization.
4. Explain how pig differs from sql .
	Sql is declarative an Piglatin is procedural to a large extent. In Sql we largely specify”what” is to be accomplished and in Pig latin we mention “how “ a task is to be performed.A script written in Pig is essentialy converted to a mapReduce  job in the background before it is executed.
5. Explain the scalar data types in pig
•	Int-it store a four byte signed integer.
•	Long-it store a eight signed integer
•	Float-it store a four byte floating point number
•	Double-it store a eight byte floating point number
•	Chararray-constant chararrays are represented by single quotes
•	Bytearray-there is no way to specify a bytearray constant. 
