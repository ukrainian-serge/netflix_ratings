<p align="center">
    <img src="./netflix.png" alt="logo" width="1024" height="475"/>
</p>

# Netflix rating data exploration
*Analysis of ratings using pandas and `data.world` package for dataset version control*

---

### Data Question: 
- do Netflix subscribers prefer older or newer movies?

We'll approach it with "split-apply-combine" method:
1. split the data into groups by creating a groupby object from the original DataFrame;
2. apply a function, in this case, an aggregation function that computes a summary statistic (you can also transform or filter your data in this step);
3. combine the results into a new DataFrame.
