![](assets/images/code_review.png)
Make sure these boxes are checked before submitting/approving the PR

# General
- [ ] The code works
- [ ] The code is easy to understand
- [ ] Follows coding conventions
- [ ] Names are simple and if possible short
- [ ] Names are spelt correctly
- [ ] Names contain units where applicable
- [ ] No hard coded constants that could possibly change in the future
- [ ] All variables are in the smallest scope possible
- [ ] There is no commented out code
- [ ] There is no dead code (inaccessible at Runtime)
- [ ] No code that can be replaced with library functions
- [ ] Variables are not accidentally used with null values
- [ ] Variables are immutable where possible
- [ ] Code is not repeated or duplicated
- [ ] No complex/long boolean expressions
- [ ] No negatively named boolean variables
- [ ] No empty blocks of code
- [ ] Ideal data structures are used
- [ ] Constructors do not accept null/none values
- [ ] Catch clauses are fine grained and catch specific exceptions
- [ ] Exceptions are not eaten if caught, unless explicitly documented otherwise
- [ ] Files/Sockets and other resources are properly closed even when an exception occurs in using them
- [ ] `null` is not returned from any method
- [ ] == operator and === (and its inverse !==) are not mixed up
- [ ] Floating point numbers are not compared for equality
- [ ] Loops have a set length and correct termination conditions
- [ ] Blocks of code inside loops are as small as possible
- [ ] No methods with boolean parameters
- [ ] No object exists longer than necessary
- [ ] No memory leaks
- [ ] Code is unit testable
- [ ] Test cases are written wherever possible
- [ ] Methods return early without compromising code readability
- [ ] Performance is considered
- [ ] Loop iteration and off by one are taken care of

# Architecture
- [ ] Design patterns if used are correctly applied
- [ ] A class should have only a single responsibility (i.e. only one potential change in the software's specification should be able to affect the specification of the class)
- [ ] Classes, modules, functions, etc. should be open for extension, but closed for modification
- [ ] Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program
- [ ] Classes should be designed to be easily extensible
# API
- [ ] APIs and other public contracts check input values and fail fast
- [ ] API checks for correct oauth scope / user permissions
- [ ] Any API change should be reflected in the API documentation
- [ ] APIs return correct status codes in responses

# Logging
- [ ] Logging should be easily discoverable
- [ ] Required logs are present
- [ ] Frivolous logs are absent
- [ ] Debugging code is absent
- [ ] No `print_r`, `var_dump` or similar calls exist
- [ ] No stack traces are printed

# Documentation
- [ ] Comments should indicate WHY rather that WHAT the code is doing
- [ ] All methods are commented in clear language.
- [ ] Comments exist and describe rationale or reasons for decisions in code
- [ ] All public methods/interfaces/contracts are commented describing usage
- [ ] All edge cases are described in comments
- [ ] All unusual behaviour or edge case handling is commented
- [ ] Data structures and units of measurement are explained


# Security
- [ ] All data inputs are checked (for the correct type, length/size, format, and range)
- [ ] Invalid parameter values handled such that exceptions are not thrown
- [ ] No sensitive information is logged or visible in a stacktrace



/****source https://gist.github.com/nerandell/c5b2e94c5af73768255f8cc46c508260#file-code-review-checklist-md****/