# me-style
Coding style checklist 

## Design 

1. Things that change for the same reasons - should be grouped together (database stuff, business rules)
2. Stuff that does not change for the same reasons - should be separate (business rules, formatting)
3. Single responsibility - imaging roles of diffrent people (clerk, accountant, business person) - if changes will come from these diffrent people, they should not be coupled

### Views 
1. Views should just display stuff - do not mangle any complexity here 
