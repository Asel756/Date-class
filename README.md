Key Methods:
Date(int day, int month, int year)	Constructor that validates the date before creation.
isValidDate(int day, int month, int year)	Checks if a date is valid using LocalDate.
updateDate(int day, int month, int year)	Updates the date if valid, otherwise fails gracefully.
getDayOfWeek()	Returns the day of the week (e.g., "MONDAY").
calculateDifference(Date otherDate)	Computes the difference in days between two dates.
printDate()	Prints the date in a readable format (e.g., "MAY 10, 2022").
compareTo(Date other)	Enables sorting by comparing dates (year → month → day).

Reliable Validation – Uses LocalDate to ensure correct dates (e.g., rejects February 30).
Modern Java Time API – Avoids manual leap-year calculations.
Sorting Support – Implements Comparable<Date> for easy sorting.
Readable Output – Formats dates clearly (e.g., "AUGUST 15, 2020").

Simpler Code - Uses Java's built-in LocalDate for all date operations
Automatic Validation - LocalDate.of() checks for valid dates
Easy Sorting - Just call Collections.sort(dates)
Clean Output - Prints like "MAY 10, 2022"
