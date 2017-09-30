# MS-Apriori
MS-Apriori is extended version of Apriori to allow multiple minimum supports. In this the minimum support of a rule is expressed in terms of minimum item supports (MIS) of the items that appear in the rule. That is, each item in the data can have a MIS value specified by the user. By providing different MIS values for different items, the user effectively expresses different support requirements for different rules. Like Apriori, MS-Apriori is also based on level-wise search. It generates all frequent itemsets by making multiple passes over the data.

## Usage
`python msapriori transaction.txt parameter.txt output.txt`

**transaction.txt** has transactional data</br>
**parameter.txt** has various parameters - _MIS, maximum support difference, cannot be together, must have_ </br>
**output.txt** will contain the final output
