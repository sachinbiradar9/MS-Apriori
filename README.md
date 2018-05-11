# MS-Apriori
MS-Apriori is an extended version of Apriori to allow multiple minimum supports. In this the minimum support of a rule is expressed in terms of minimum item supports (MIS) of the items that appear in the rule. That is, each item in the data can have a MIS value specified by the user. By providing different MIS values for different items, the user effectively expresses different support requirements for different rules. Like Apriori, MS-Apriori is also based on level-wise search. It generates all frequent itemsets by making multiple passes over the data.

## Usage
`python msapriori.py transaction_file parameter_file output_file`

## Credits
[Dr. Bing Liu](https://www.cs.uic.edu/~liub/)
