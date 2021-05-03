 # Skill Drill: Putting it ALL together


A VP at your company has written a SQL for a report that shows how much time is being lost due to flight delays by Airport and Carrier.  It is performing below expectations.  Your task is to  use the optimizing skills you learned in Unit 8 to get this query to run as fast as possible.

The initial query takes between 15-20 seconds.  The final query should be <2 seconds.

**Instructions:**

1. In this skill drill, we will use files from the class activity. To begin, upload the `airportCodes.csv` to your Colab environment.

2. Try the optimizations in this order, noting the runtime after each step:

   * Storage: Optimize how the data is stored

   * Partition:  Select an appropriate column and partition the data.

      * You can combine Steps 1 and 2.

   * Shuffling:  Optimize shuffling.

   * Cache: Which tables to cache.

      * **Hint:** Remember to uncache at the end.

   * Other: Throughout your SQL and Spark lessons, other best practices were mentioned.  Try implementing the following: 

      * Lowering the number of columns.
      
      * Filtering the data early on.

---
