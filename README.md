RANSAC ALGORITHM PROJECT
RANSAC is a resampling technique that generates candidate solutions by using
the minimum number observations (data points) required to estimate the underlying
model parameters.


RANSAC Algo.
1: Select randomly the minimum number of points required to determine the model
parameters.
2: Solve for the parameters of the model.
3: Determine how many points from the set of all points fit with a predefined tolerance .
4: If the fraction of the number of inliers over the total number points in the set
exceeds a predefined threshold τ , re-estimate the model parameters using all the
identified inliers and terminate.
5: Otherwise, repeat steps 1 through 4 (maximum of N times).
