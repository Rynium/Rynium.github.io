=begin
What did you learn from the refactoring process? What did you see during the demo that you can do going forward? How did your approach differ from my approach? How were our approaches the same? If you were to do this again, how would you approach it?

How did the demonstration of refactoring affect the way you went about solving your homework assignment?
=end

Refactoring has taught me the benefits of breaking up code into blocks with a single specific job. Something I noticed during the demo was how helpful the rake tests can be while manipulating code. This is just a constant way to check for whether or not something does what we want it to. My approach was similar, as year and month were first validated to ensure that they were valid. Following that my code used a method with an if/eslif statement to route the day to a day validator for 31, 30, 29, & 28 days. A leap year checker was built - in to this code to condense lines. If I were to do this again I would make it it's own separate function. This would allow testing while building the code, and easy recognition of the problems as they're identified by the tests. 
