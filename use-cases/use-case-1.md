# USE CASE: 1 Produce a Report on the Salary of Employees of a company

## CHARACTERISTIC INFORMATION

### Goal in Context

As an HR advisor I want to produce a report on the salary of all employees so that I can support financial reporting of the organisation.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the company.  Database contains current employee salary data.

### Success End Condition

A report is available for the HR advisor to provide to finance.

### Failed End Condition

No report is produced.

### Primary Actor

HR advisor.

### Trigger

A request for finance information is sent to the HR advisor.

## MAIN SUCCESS SCENARIO

1. Finance request salary information for the company.
2. HR advisor captures name of the company to get salary information for.
3. HR advisor extracts current salary information of all employees.
4. HR advisor provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. HR advisor informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0