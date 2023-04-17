# Google Sheets-script-for-validating-EU-VAT-numbers-and-retrieving-consultation-number
Facing incorrect VAT validation results and inability to retrieve consultation numbers in a Google Sheets script.

I am currently working on setting up a Google Sheets script for my company to easily validate EU VAT numbers and generate consultation numbers for reporting purposes. The code I have works to some extent, returning either "valid" or "invalid" depending on whether the VAT numbers are valid. However, I'm facing a couple of issues:

I've set up a restraint to delay the requests, thinking that the script might be returning incorrect results (false negatives) due to processing too many requests too quickly. However, the issue persists even after implementing the delay. I'm not sure what could be causing this problem.
I've tried to set up the script to return consultation numbers, which are important for our documentation. However, it doesn't return any consultation numbers at all. I'm not sure why this is happening or how to fix it.


