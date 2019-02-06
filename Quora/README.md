### Quora "Insincere questions" dataset release

This zip archive contains the following files:

* `README.md` (this file): an overview of the dataset
* `TOS.txt`: the terms of service for this dataset
* `insincere.csv`: the dataset

Rows in insincere.csv each have three comma-delimited fields:

* alphanumeric identifier
* question text (in double quotation marks if the question contains a comma)
* binary label: 0 for sincere, 1 for insincere

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

* Has a non-neutral tone
    * Has an exaggerated tone to underscore a point about a group of people
    * Is rhetorical and meant to imply a statement about a group of people
* Is disparaging or inflammatory
    * Suggests a discriminatory idea against a protected class of people, or seeks confirmation of a stereotype
    * Makes disparaging attacks/insults against a specific person or group of people
    * Based on an outlandish premise about a group of people
    * Disparages against a characteristic that is not fixable and not measurable
* Isn't grounded in reality
    * Based on false information, or contains absurd assumptions

Besides the terms contained in the file TOS, this dataset is subject to Quora's Terms of Service: <https://www.quora.com/about/tos>.
