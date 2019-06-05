# Class: Teacher

## Attributes:
- **TeacherId** (string)
- **FullName** (string)
- **TeachingGrades** (array)
- **Subject** (array)
- **Pay** (float)
- **FullTime** (boolean)

## Methods:
- **UpdateTG** (modifies teaching array based on semester master schedule)
- **UpdatePay** (based on performace evalueation, pay = pay*(increase))
- **ModifyFullTime** (set to True if hired fulltime)
- **UpdateSubject** (modify subjects taught based on semester master schedule)