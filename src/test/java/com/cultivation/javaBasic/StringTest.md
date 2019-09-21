## should_be_immutable()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/java-string-replace
2. Why the test failed at first?
* Because the value set to empty.
3. Why you corrected the test that way?
* Based on the knowledge point, the replace method would replace the indicated word (first parameter) of the String variable using the word supplemented by the second parameter.
4. Do you have further questions on this knowledge point?
* No other concerns

## all_modification_method_will_create_new_string()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/java-string-trim-method-example/
2. Why the test failed at first?
* Because the value set to empty.
3. Why you corrected the test that way?
* Based on the assertEquals, it is expected to be false since the first string (originalString) has a trail of whitespace and that is considered as part of the string. So when the two strings (originalString and modifiedString) are compared, it will result into false since the second string has trimmed all whitespace after the last character of the string
4. Do you have further questions on this knowledge point?
* No other concerns

## will_create_new_string_when_concat()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/string-concatenation-in-java
2. Why the test failed at first?
* Because the value set to empty.
3. Why you corrected the test that way?
* Based on the assertEquals, it is expected to be false since the first string (originalString) has added the value of "Part two." into the originalString. Since the originalString value was copied to the copyOfOriginalString and never modified afterwards, it is different from the originalString.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_taken_string_apart()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://howtodoinjava.com/java/string/java-string-substring-example/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the expectedResult, it should only substring the part of the originalString that had the part of "is great"
4. Do you have further questions on this knowledge point?
* No other concerns

## should_taken_string_apart_continued()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://howtodoinjava.com/java/string/java-string-substring-example/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the expectedResult, it should only substring the part of the originalString that had the part of "is"
4. Do you have further questions on this knowledge point?
* No other concerns

## should_break_string_into_words()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/split-string-java-examples/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, it should split the sentence into different parts of an Array through whitespace being the regex.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_break_string_into_words_customized()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/split-string-java-examples/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, it should split the sentence into different parts of an Array through backslash being the regex.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_create_ascii_art()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.baeldung.com/ascii-art-in-java
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, it should base the height as a for loop and the width as an internal for loop.
* No other concerns

## should_calculate_checksum_of_a_string()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://stackoverflow.com/questions/20500760/working-out-a-checksum-of-mixed-characters
2. Why the test failed at first?
* Because the value set to .
3. Why you corrected the test that way?
* Based on the knowledge point, it would get the char equivalent where the charAt is positioned in the string and it would parse the value into int and add the value to the sum.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_convert_unicode_escape()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/unicode-system-in-java
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, the characters in the expectedResult have equivalent unicode that can be placed in the code. It would read as the unicode but when it is executed, it will result into the character equivalent to that unicode.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_reverse_a_string()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/stringbuilder-reverse-in-java-with-examples/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, there is a built-in method in StringBuilder class that would return a reverse string of the given string.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_compare_string_with_different_cases()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.javatpoint.com/java-string-equals
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, equals would result only as true if the two values being compared are equal to each other. If the method used is equalsIgnoreCase it would ignore the case of the String and if the two values are the same even if with different cases, it would still result into true.
4. Do you have further questions on this knowledge point?
* No other concerns

## should_format_string()

1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
* https://www.geeksforgeeks.org/java-string-format-examples/
2. Why the test failed at first?
* Because the value set to null.
3. Why you corrected the test that way?
* Based on the knowledge point, the method format would replace all the indicated format value of the string with the supplemented objects after the first paramenter.
4. Do you have further questions on this knowledge point?
* No other concerns