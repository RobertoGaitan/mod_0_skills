# Class: Student

## Attributes:
- **StudentId** (string)
- **FullName** (string)
- **ClassGrades** (array)
- **GradeLevel** (integer)
- **CreditsEarned** (float)
- **Graduated** (boolean)

## Methods:
- **CalculateGPA** (divides sum of ClassGrades by number of grades)
- **AddCreditsEarned** (based on grades, add credits)
- **AdvanceGL** (advances GradeLevel based on CreditsEarned)
- **AddSticker** (append a sticker item into the Stickers array)
- **GraduateStudent** (True if Credits Earned achieved minimum)