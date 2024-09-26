# Hibernate @Fetch(FetchMode.JOIN)

The original idea is from  
https://medium.com/@antelll/solving-the-hibernate-n-1-problem-best-practices-and-strategies-fa437d327a98

See also
https://medium.com/jpa-java-persistence-api-guide/hibernate-optimization-with-batchsize-and-batch-size-configuration-579bf759fc05

This example shows @BatchSize At Collection Level


# @BatchSize At Collection Level
Author has OneToMany relationship to Book

Applying @BatchSize(size=N) at collection level loads the books of N authors at once when iterating over Authors 


