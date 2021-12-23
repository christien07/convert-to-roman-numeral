# convert-to-roman-numeral

Pass in any number >= 0 when calling the function and the number will be converted into a Roman Numeral.

Numbers >= 4000 will not display specific characters above typical Roman Numerals (I, V, X, L, C, D, M).

Negative numbers and 0 are not valid inputs and will not return a valid Roman Numeral.

This function checks for all typical cases and also includes specific cases (like 4, 9, 49, 90 and so on that may return "unexpected values" - 9, of course, would return IX not VIIII (or worse IIIIIIIII)).

5000 would return MMMMM, not the otherwise specific character V with a "bar" above.
