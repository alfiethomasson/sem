# USE CASE: 5 Add details of a new employee to ensure they get paid

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to add a new employee's details so that I can ensure the new employee is paid.

### Scope

Company.

### Level

Primary task.

### Preconditions

Employees details are not already registered.  

### Success End Condition

Employees details are entered correctly and they are paid the correct amount.

### Failed End Condition

1. No details are added.
2. Employee is not paid.

### Primary Actor

HR advisor.

### Trigger

A new employee joins the company.

## MAIN SUCCESS SCENARIO

1. HR advisor checks if new employees details are entered.
2. HR advisor adds new details.
3. HR advisor ensures details are correct.
4. Employee is correctly paid.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor informs finance no employee exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0