# Gurobi-optimization-project

### MATH3202 Operations Research & Mathematical Planning

ELECTRIGRID supplies electricity to a small region from four generators running on natural gas. Over the years, a network of transmission lines were built, running from the generators to substation nodes around the region, as shown in the following map:

![ELECTRIGRID](https://user-images.githubusercontent.com/67094150/205865389-12b44f32-7df4-405c-a71c-c2b8e5d8cfcf.png)

The following data files are provided:

- [nodes.csv](https://courses.smp.uq.edu.au/MATH3202/2021/csv.php?file=nodes) gives the location of each node (units are kilometres) and the current demand (MW) at that node
- [grid.csv](https://courses.smp.uq.edu.au/MATH3202/2021/csv.php?file=grid) gives all the connections between the nodes that make up our grid

The red nodes on the map show the locations of the generators. Due to various factors, these generators have different capacities and costs for producing electricity.

Utilising Linear, Integer and Dynamic Programming techniques as well as mathematical formulation, we aim to optimize the total expected cost for meeting different conditions and requirements.
