# USE CASE: 3 Produce a Report on the Salary of Employees of a in a given department

## CHARACTERISTIC INFORMATION

### Goal in Context

As an department manager I want to produce a report on the salary of employees in my department so that I can support financial reporting for my department.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the department.  Database contains current employee salary data.

### Success End Condition

A report is available for the Department Manager to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

Department Manager.

### Trigger

A request for finance information is sent to the department manager.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for a given department.
2. Department manager captures name of the department to get salary information for.
3. Department manager extracts current salary information of all employees of the given department.
4. Department manager provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. Department manager informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0