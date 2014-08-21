## CSV Validator

#### Objective:

Provide a tool for a user to upload a CSV in a specific format which validates against a series of rules.
Then provide the ability for the user to edit the invalid fields and export back to CSV.

Example CSV can be found in the repo

#### Validation Rules:
- No two SKUs can be the same
- All rows must contain the following fields SKU, Size, Colour, Flavour
- All rows must contain either a Retail Price or a Wholesale Price
- The combination of Size, Colour and Flavour must be unique
