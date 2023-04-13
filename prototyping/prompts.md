# Prompts to create content for use in prototyping.

## Generate names of people
```
Generate [number results] male and female names from different nationalities. These should be in English and be made up of first and last names. Please return the names as [format] with separate properties for the given and family name. Also include a gender property. Make sure to include at least [number names] names where the family name or the given name are [number characters] or more characters in length. Don't include a "length" property in the output.
```
Options:
- Number results - Total results you expect. 50 or more tends to generate good variance
- Format - I suggest JSON, but you could use "list", "CSV" or "table"
- Number Names - how many of the *Number Results* should be long (good for prototyping). Suggest 5-7
- Number Characters - Length of one of the names. 15 to 20 gives good variance.

## Generate job titles in a given industry

## Generate address/contact information examples for a given country