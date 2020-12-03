# amazon-mapreduce

A DSBA 6190 assignment where I used Apache Hadoop's MapReduce to find whether Amazon reviews containing the words "reviews" or "comments" would different from the overal rating for each product. The ouput is the number of products that falls into bins for the difference between each product's overall rating and the average reviews containing "reviews" or "comments". 

Output: 
| difference |  count  |
|:----------:|:-------:|
|    0<x≤2   |  902430 |
|    2<x≤3   |  71836  |
|    3<x≤5   |  29527  |


The results cannot prove reviews mentioning “reviews” or “comments” will likely be different from the overall rating for a product. 