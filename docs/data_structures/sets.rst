Sets
====

Definition
-----------

A set is an abstract data type that is a well-defined, unordered collection of elements. Sets contain only distinct elements. Sets are one of the most fundamental concept in mathematics since they were developed near the end of the 19th century.

Unlike various other data structures, elements are more often tested for membership within a set rather than the retrieval of a specific element for said set.


.. code-block:: python
  # To create a set in Python, we use curly parenthesis, quite similar to creating a dictionary 
  # Let's create a set of numbers ranging from 1 to 7
  A = {1, 2, 3, 4, 5, 6, 7}
  print ('Set A: ', A)

  # Since a set only holds distinct values, what would happen if we attempted to create the following
  B = {1, 2, 3, 3, 3, 4, 5, 5, 6, 6, 7}
  print ('Set B: ', B)

  # Assert that A is in fact equal to B since we discard the additional 3, 5 and 6 values
  assert A == B


Operations
-----------

Union
###########

Intersection
###########

Difference
###########

Symmetrical Difference
###########
