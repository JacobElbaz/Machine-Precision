e = abs(3.0*(4.0/3.0-1)-1)

# simple algo to find the machine epsilon of my computer:
epsilon = 1.0
while (1.0 + 0.5 * epsilon) != 1:
    epsilon = 0.5 * epsilon

print("\nabs(3.0*(4.0/3.0-1)-1) = {}".format(e))
print("machine epsilon = {}".format(epsilon))

# correcting precision error:
e = e - epsilon

print("abs(3.0*(4.0/3.0-1)-1) - machine epsilon = {}".format(e))
