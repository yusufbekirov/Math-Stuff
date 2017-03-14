import math


def cartesian_to_polar(arg1, arg2):
    r = float(math.sqrt((arg1 * arg1) + (arg2 * arg2)))
    theta = float(math.atan(arg2 / arg1))

    print "Polar cooridinates are: (%r, %r)" % (r, theta)


def polar_to_cartesian(arg1, arg2):
    x = arg1 * math.cos(arg2)
    y = arg1 * math.sin(arg2)

    print "Cartesian cooridinates are: (%r, %r)" % (x, y)


print "Welcome to the Cartesian<->Polar Coordinate Calculator"
choice = float(raw_input("Enter 1 for Cartesian->Polar or Enter 2 for Polar->Cartesian:"))

if choice == 1:
    x = float(raw_input("Please enter the x: "))
    y = float(raw_input("Please enter the y:"))

    cartesian_to_polar(x, y)

if choice == 2:
    r = float(raw_input("Please enter the r value:"))
    theta = float(raw_input("Please enter the theta value:"))

    polar_to_cartesian(r, theta)
