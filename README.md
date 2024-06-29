# Multiregional-Coverage-Path-Planning-For-Single-Energy-Constrained-UAV
It presents an approach to optimizing lawn mower paths for covering multiple polygons, employing advanced optimization algorithms and strategic path planning.
The polygons are generated using a method that involves randomizing the number of sides, 
radius, and position within designated sub-areas, ensuring that they are fully contained in subareas and non-overlapping.
To cover each polygon efficiently, four distinct lawn mower motion strategies are implemented: Left to Right and Right to Left, Down to Up and Up to Down. These strategies ensure better coverage of each polygon while maintaining consistency in movement patterns.
ACO algorithm is used to optimize the traversal path between the centroids of the polygons.
The final phase of the project involves the visualization of the generated polygons and the optimized traversal path using Matplotlib. The visualization not only displays the polygons but also the traversal path optimized by the ACO algorithm and the coverage paths generated by the lawn mower motion strategies.
