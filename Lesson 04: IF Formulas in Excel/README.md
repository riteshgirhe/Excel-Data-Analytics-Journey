# Lesson 04: IF Formulas in Excel

In this lesson I learned how to use the IF function in Excel to check a condition and show a result. I also practised IF with AND and OR to check more than one condition.

## What I Learned

- The syntax of the IF function
- Comparison operators: `>`, `<`, `=`, `>=`, `<=`, `<>`
- Showing results like Pass/Fail and Yes/No
- Using IF with AND (all conditions must be true)
- Using IF with OR (at least one condition must be true)

## Syntax

```
=IF(logical_test, value_if_true, value_if_false)
```

## Files

- **Lesson_04_IF_Formulas_Notes.xlsx**: 10 questions and answers, with basic IF examples on employee data (result, salary, age, bonus and marks).
- **Lesson_04_Practice_AND_OR.xlsx**: Practice with IF, AND and OR using student results, voting age and employee promotion.

## Examples

```
=IF(E2>=40,"PASS","FAIL")
=IF(AND(C2>=35,D2>=35,E2>=35),"Pass","Fail")
=IF(OR(C2>=130,D2>=5),"YES","NO")
```

## Practice

1. Change the marks and check how the result changes.
2. Change AND to OR and compare the answers.

## Next Lesson

[Lesson 05: Nested IF and IFS](../Lesson%2005%20-%20Nested%20IF%20and%20IFS/)
