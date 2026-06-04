# Least-squares problems: Satellite connection back online
## Mission LAIKA: Satellite connection back online

Due to a collision with space debris, the trajectory of a satellite has been altered. To understand its movement, we need to determine its new orbit. We know the orbit will be one of three types: parabolic, elliptical, or hyperbolic. 
<img scr="../MissionLAIKA/img/case15-1.png">


The trajectory of the satellite can be described by a polar equation: 
<img scr="../MissionLAIKA/img/case15-2.png">


$$ r= b+e(r cos(\theta)) $$

$r$ \hspace{2mm}   distance from centre of attraction\
\color{white}{$r$} \hspace{2mm}  \color{black} (in thousands of kilometres)\
$\theta$ \hspace{2mm}  angular position\

The parameters b and e, which define the shape and characteristics of the orbit, are currently unknown. 



## Exercise
Using observational data for $r$ and $\theta$, we can apply linear regression to estimate $b$ and $e$. With these approximations, we can determine whether the satellite's new path is parabolic, elliptical, or hyperbolic, and better predict its future trajectory. \\

Try to find these approximations for $b$ and $e$ using the following observations.

\begin{tabular}{l|lllll}
$r$ & $3.00$ & $2.30$ & $1.65$ & $1.25$ & $1.01$ \\ \hline
$\theta $ & $0.88$ & $1.10$ & $1.42$ & $1.77$ & $2.14$%
\end{tabular}

<img scr="../MissionLAIKA/img/case15-3.png">






## Grasple
