# enrollmentMaster
Enrollment

ENROLLMENT SETUP db Module Structure

-gradelevel
*id
*name

-schoolyear
*id
*name

-group
*id
*name

-department
*name


-teacher
*id
*name
*group
*department

-section
*id
*name
*description
*group
*gradelevelid
*gradelevel


-accounting
*id
*name
*description
*debit_amount
*credit_amount
*category
*isbill
*ispayment
*group



-requirements
*id
*name
*description
*ispass
