# About project

Twitter provides a service for posting short messages. In practice, many of the tweets are very similar to each other and can be clustered together.
By clustering similar tweets together, we can generate a more concise and organized representation of the raw tweets, which will be very useful for many Twitter-based applications (e.g., truth discovery, trend analysis, search ranking, etc.)
the tweets are clustered using **Jaccard distance** metric and **K-means clustering** algorithm.


# Main steps

## Tweets Preprocessing:
   • tweet IDs and timeStamps are removed.
   •words that starts with the symbol '@', e.g., @AnnaMedaris, are removed.
   • hashtag symbols are removed, e.g., #depression is converted to depression.
   • any URL are removed.
   • every word is converted to lowercase.
   
## K-Means clustering algorithm:
 **K-means clustering algorithm is implemented from scratch, without using any machine learning libraries.**
  1. The code uses "bbchealth.txt" by default for the tweets data. - A user can change the url path to another     data file as desired from the given files.
  2. The code uses, "3 clusters" by default and performs "5 experiments" one after another.
  3. user can change the default value of initial clusters (k) and number of experiments to be performed.
  4. The program returns the value of SSE (sum of squared error) and size of each cluster after every experiment   (plotted).
  

# Team Members
- [Heba Tarek](https://github.com/hebatarekkamal)
- [Rana Ahmed](https://github.com/RanaAhmed2022)
- [Raneem Loay](https://github.com/RaneemLoay)
- [Salwa Ahmed](https://github.com/salllwaaa)
- [Samaa Sabry](https://github.com/samaasabri)
- [Sohyla Tarek](https://github.com/Sohyla31)
- [Sumaya Bile]()



