# Logic and Language project code

Our model (the run_patterns() function) takes as argument a list of patterns and a SNLI data set.

Run_patterns can be used with a single pattern as argument to calculate the precision of that pattern. The precision of a pattern is the percentage correct labels of the given labels. This is the chance that a label given by this pattern is correct.

When run_patterns is ran with multiple patterns as argument, the precisions of the patterns are used inside the function to decide the final label of an example. This is the label of the pattern with the highest precision on that example. The total precision of the patterns used together is printed. The number of covered examples is also printed. Covered examples are examples that satisfy at least one pattern, and hence received a label from the model.
