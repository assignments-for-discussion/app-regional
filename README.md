# Region-sensitive App

The purpose of this starter-repo is to have a short code snippet for mutual review and discussion.

We need an app with two screens:

1. Language & Region-selection screen
1. Small menu of three breakfast items and their prices

The first screen appears only once after installation.
The content of the second screen depends on the selection in the first.

For example, if a user chooses Language as English and Region as India, the menu will read:

- Idly - ₹15
- Dosa - ₹25
- Vada - ₹20

If the Language is Malayalam and Region is Dubai, the menu will read:

- ഇഡ്ലി - 15 د.إ
- ദോശ - 25 د.إ
- വട - 20 د.إ

Notes: 

- Choose any two languages, regions and breakfast-items of your liking
- The items remain same in all languages, only the language of display changes.
- In the above example,  د.إ is the symbol for dirham, the currency in Dubai.
- Currency conversion for the amount is not required. Just the same amount is displayed with a different symbol.

**Tests**: Write tests to cover this functionality. Ensure that passing tests will give confidence - When the report is 'passed', we don't need to re-run any tests manually.
