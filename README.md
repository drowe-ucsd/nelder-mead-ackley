# nelder-mead-ackley
A Houdini visualization of Nelder-Mead optimization running on the Ackley function (created for CSE 274 Winter 2022).

<img src="halfres_gif.gif"/>

This visualization shows the Ackley function (a nonconvex function commonly used to test optimization functions) as well as several instances of Nelder-Mead optimization running in parallel.  Nelder-Mead, a heuristic method for nonlinear derivative-free optimization, uses evaluations of the objective function on the vertices of a simplex (here, a triangle) to determine the next positions for the vertices of the simplex.

Repository contains Houdini files (with VEX code), rendered video, and a still frame from the video.
