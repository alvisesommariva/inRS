# inRS
Indomain routines for NURBS, composite Bezier or bivariate parametric splines domains

» IN_RS: Matlab routine for points indomain on NURBS-shaped planar domains (2022) 
A new indomain routine suitable to establish what points in a bivariate set are inside NURBS-shaped domains (as well as with boundaries that are composite Bezier spline or defined by parametric splines).

» Object: IN_RS: Matlab routine for points indomain on NURBS-shaped planar domains. 

The main folder IN_RS contains:

inRS.m, a new routine for indomain over NURBS-shaped domains;
inRS_21.m, an old routine for indomain over NURBS-shaped domains;
inRSpoly2.m, a routine for indomain over NURBS-shaped domains (based on approximating the domain with a polygon, it requires inpoly2 by D. Engwirda);
demo_nurbs_indomain_01.m, demo_nurbs_indomain_02.m, demo_nurbs_indomain_03.m are demos, useful to define the domains and to understand how to use the indomain routine.
demo_nurbs_indomain_04.m, evaluates the performance of our two indomain routines for NURBS presented in [1] and [2], comparing them to one in which the NURBS boundary is approximated by a polygon, finally using inpoly2 by D. Engwirda. To make that comparison, please download the routine inpoly2 and save it in the IN_RS folder.

» Sources: 

Papers:
[1] A. Sommariva and M. Vianello, Low-cardinality Positive Interior cubature on NURBS-shaped domains, [PDF] (submitted),
[2] A. Sommariva and M. Vianello, inRS: implementing the indicator function for NURBS-shaped planar domains (submitted).

Codes:
Last version: [MATLAB CODES (zip file)],
» Last update: January 06, 2022. 
