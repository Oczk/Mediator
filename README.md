# Mediator
Simple app designed with Mediator pattern.
Checks if given text fulfills given validator's rules.

Contains 6 text validators classes:
- TXT only alphabet letters a-z, A-Z, underscore, spacebar, dot, comma;
- ALFA like txt + digits;
- NUM only digits;
- POINT text should begin with dash;
- BIG only big letters;
- EVEN only even digits;

Format:
text;VAL;VAL;...

Example:
23555564566;NUM
bomb;TXT;BIG

Return 'true' if text is consistent with validators or 'false' if not.
