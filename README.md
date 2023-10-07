# Things I'd do over if I had the chance

Regexes can quickly become unruly. My advice: Isolate the regex module. Write tests for all languages in the project.
Helpful especially when rewriting.

## For beginners or those unfamiliar with regex

Regexes are useful because they're ubiquitous and powerful. They're implemented in all major programming languages and all editors include them. You'll be surprised how universal they are. It's a great idea to learn regexes before learning any programming language. They're very beginner-friendly, too: you see useful results and you naturally want variables to store captures. The [now you have two problems](https://blog.codinghorror.com/regular-expressions-now-you-have-two-problems/) take is dumb because *everything's* hard to understand -- especially to a beginner. The question's the proficiency pay-off, and regexes pay off. 

But the problem is precisely that they're so beginner-friendly, that we have no protection for these two problems:

1. regex syntax differs between languages.
2. regex can fail silently; we have to catch errors and write good tests

It's *impossible* for beginners to understand [why writing exceptions is useful.](https://www.youtube.com/watch?v=jmL_zRx59_Q&t=5520s)
This maturity is required to properly test regexes.
But we might require a new language as soon as this maturity is obtained.
As we learn our new language, regular expressions feel like a common ground, but we have to be sure.
We're stuck using the old library until we know the syntax and how to write tests in the new language.
