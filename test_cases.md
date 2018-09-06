###borderline cases, such as a list with 0 or 1 elements
   count_unique(['h'])
   count_unique([ ])


###typical cases, such as a list with a few duplicates or no duplicates

   count_unique(['a','a','b','b','c','c' ])
   count_unique(['a','b','c' ])


###impossible cases where the method should not work
   count_unique(null)


###extreme cases, such as a huge list
   count_unique(['a','b','c','c','c','d','e','f','g','g','g','h'])



