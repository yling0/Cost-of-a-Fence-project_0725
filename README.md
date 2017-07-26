# Cost-of-a-Fence-project_0725

## Algorithm (pseudocode)

~~~~
input perimeter in foot
input fenceType
input nGates

if nGates < 1 or nGates > 3:
  print "invalid number of gates"
  input nGates

if fenceType is "wooden":
  cost = (25\*perimeter + nGates\*150)\*(1 + 0.06) + 50
else if fenceType is "chain-link":
  cost = (15\*perimeter + nGates\*150)\*(1 + 0.06) + 50
else:
  print "fenceType invalide. please enter either wooden or chain-link"
~~~~
