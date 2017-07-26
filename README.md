# Cost-of-a-Fence-project_0725

## Algorithm (pseudocode)

input perimeter in foot

input fenceType

input nGates

if nGates < 1 or nGates > 3:

$\qquad$  print "invalid number of gates"

$\qquad$  input nGates

if fenceType is "wooden":

$\qquad$  cost = (25\*perimeter + nGates\*150)\*(1 + 0.06) + 50

else if fenceType is "chain-link":

$\qquad$  cost = (15\*perimeter + nGates\*150)\*(1 + 0.06) + 50

else:

$\qquad$  print "fenceType invalide. please enter either wooden or chain-link"
