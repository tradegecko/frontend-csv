## CSV Validator

#### Objective:

Provide a tool for a user to upload a CSV in a specific format which validates against a series of rules.
Then provide the ability for the user to edit the invalid fields and export back out the updated CSV.

A valid example CSV can be found in the repo.

#### Validation Rules:

- No two SKUs can be the same
- All rows must contain the following fields SKU, Size, Flavour, Icing
- All rows must contain either a Retail Price or a Wholesale Price
- The combination of Size, Flavour and Icing must be unique

#### Extra

- Feel free to use a JS framework to do some of the heavy lifting. 
- You are in no way expected to implement CSV parsing in JS. Check out [PapaParse](http://papaparse.com/) instead.
- Please use git/github to build your project, and provide meaningful commits, your process is just as important as your solution.
- Get in touch if you have any questions.
