# USE CASE: 8 Delete details of employee in compliance with data retention legislation

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to delete an employee's details so that the company is compliant with data retention legislation.

### Scope

Company.

### Level

Primary task.

### Preconditions

Employees details are required to be deleted.

### Success End Condition

Employees details are deleted in compliance with data retention legislation

### Failed End Condition

1. Details are retained incorrectly.
2. Details are not in compliance with legislation.

### Primary Actor

HR advisor.

### Trigger

An employee requires their details to be deleted.

## MAIN SUCCESS SCENARIO

1. HR advisor accesses employees details
2. HR advisor deletes the required details.
3. HR advisor ensures details are deleted correctly.
4. Deleted details are compliant with legislation.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor informs finance no employee exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0