# Code Refactoring

## Code to Refactor
```[LANGUAGE]
[CODE_TO_REFACTOR]
```

## Context
Purpose: [WHAT_THE_CODE_DOES]
Current issues:
- [ISSUE_1] (e.g., hard to test, duplicated logic)
- [ISSUE_2]
- [ISSUE_3]

## Goals
What I want to improve:
- [ ] Readability
- [ ] Maintainability
- [ ] Testability
- [ ] Performance
- [ ] Extensibility
- [ ] [OTHER_GOALS]

## Constraints
- Must maintain: [BACKWARD_COMPATIBILITY/API_CONTRACT/etc.]
- Cannot change: [CONSTRAINTS]
- Must preserve: [BEHAVIOR_TO_PRESERVE]

## Request
Help me refactor this code by:

**Analysis:**
1. Identify code smells:
   - Long methods
   - Large classes
   - Duplicated code
   - Dead code
   - Complex conditionals
   - Primitive obsession
   - Feature envy
   - Data clumps

2. Assess current design issues:
   - Tight coupling
   - Low cohesion
   - Violation of SOLID principles
   - Poor separation of concerns

**Refactoring Strategy:**
1. Prioritize refactorings (high impact, low risk first)
2. Suggest step-by-step approach
3. Identify safe vs risky refactorings
4. Recommend testing strategy

**Specific Refactorings:**
1. Extract method/function
2. Extract class
3. Rename for clarity
4. Introduce parameter object
5. Replace conditional with polymorphism
6. Replace magic numbers with constants
7. Simplify complex conditions
8. Remove duplication
9. Introduce design patterns where appropriate

**Refactored Code:**
Provide the refactored version with:
1. Clear structure
2. Meaningful names
3. Single responsibility functions
4. Proper abstraction levels
5. Better error handling
6. Improved comments where needed

**Testing:**
1. Tests to ensure behavior preservation
2. Additional tests for edge cases
3. Refactoring verification steps

**Migration:**
If this is a large refactoring:
1. Breaking it into smaller steps
2. Maintaining both old and new code temporarily
3. Deprecation strategy
4. Rollout plan

Explain the reasoning behind each major refactoring decision.
