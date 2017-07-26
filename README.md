# Cost-of-a-Fence-project_0725

## Algorithm (pseudocode)

~~~~
do {
input perimeter in foot
} while (perimeter <= 0)

do {
input fenceType
} while (fenceType is not "wooden" nor "chain-link")

do {
input nGates
} while (nGates is not integer)

do {
  input nGates
} while (nGates < 1 or nGates > 3)

if fenceType is "wooden":
  cost = (25\*perimeter + nGates\*150)\*(1 + 0.06) + 50
else if fenceType is "chain-link":
  cost = (15\*perimeter + nGates\*150)\*(1 + 0.06) + 50
else:
  print "fenceType invalide. please enter either wooden or chain-link"
~~~~
