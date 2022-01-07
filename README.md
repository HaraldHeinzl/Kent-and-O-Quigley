# Kent-and-O-Quigley

Using SAS to calculate the Kent and O'Quigley measure of dependence for the Cox proportional hazards regression model

## Description

Kent and O'Quigley (1988) apply the concept of information gain to define a measure of dependence (R-squared measure) between explanatory variables and a censored response variable within the framework of the Cox model. Two SAS macros to calculate this measure are presented. The first one is based on a Newton-Raphson search and makes use of the SAS IML procedure (KENTOQNR macro). The second one is a simple grid search using SAS DATA steps and Base-SAS procedures (KENTOQGS macro). 

## References

Kent, J.T. & O'Quigley, J. (1988): Measures of dependence for censored survival data. Biometrika 75, 525-534.

Heinzl, H. (2000) "Using SAS to calculate the Kent and O'Quigley measure of dependence for Cox proportional hazards regression model." Computer Methods and Programs in Biomedicine 63, 71-76.
