# Cube
[Google](https://binaryterms.com/data-cube.html)
- Multi-dimensional structure data storage
- ![image](![img_2.png](img_2.png))
- Stores the precomputed data and eases online analytical processing (OLAP).
- Data representation: Dimensions and Facts
- Dimensions: attitude, angle or the entities with respect to which the enterprise wants to store the data
- Fact: Numeric measures
- Basic Category: Multi-dimensional Data Cube (MOLAP); Relational Data Cube (ROLAP); Hybrid Data Cube (HOLAP)
- Operation on Data Cube:
    * **Roll Up:** summarizes or aggregates the dimensions either by performing dimension reduction or you can perform concept hierarchy.
    * ![image](![img_1.png](img_1.png))
    * **Drill Down:** fragmenting into granular form
    * ![image](drillDown.png)
    * **Slice and Dice:** pick up one dimension of the data cube and then forms a sub-cube out of it.
    * ![image](img.png)