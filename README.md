# Wind Farm Layout Optimization using Genetic Algorithm

This repository contains the code for WFLOP using GA which was used as the final submission in <a href="https://www.hackerearth.com/challenges/competitive/shell-hackathon/machine-learning/shell-wind-farm-layout-optimization-16-de36c5fb">Shell.AI hackathon</a>


* WFLOP is an interesting and complex optimization problem. The key challange arises due to the high dimensionality, complex multimodality of the search space.
* Two contraints that were posed in this challange were:
** Perimeter Constraint: All the turbines must be located inside the perimiter of the farm while maintaining clearence of <b>50 meters</b> from the farm boundary
** Proximity Constraint: The distance between two turbines must be larger than a security threshold of <b> 400 meters </b> for longer lifetime of the turbine rotors.
* Please read the PDFs for detailed descrption of the problem statement, constraints, WAKE effect and other details.
* The final submission using this approach was ranked in Top-5% out of 1527 teams on Public Leader Board.


# Requirements

* Numpy
* Pandas
* Shapely
