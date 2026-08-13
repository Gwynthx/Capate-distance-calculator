# Capate-distance-calculator

**Goal:** Find the distance between Manila and Cebu.

**Requirements:** Coordinates of Manila and Cebu.
**Question:** What is the coordinates of Manila?
Look for:

-The x coordinate of Manila
-The y coordinate of Manila
-The x coordinate of Cebu
-The y coordinate of Cebu

## Step 1: Apply math library to acces the mathematecal
Enter: "import math"

## Step 2: enter coordinates of Manila

x1 = float(input("enter x1: "))

y1 = float(input("enter y1: "))

## Step 3: enter coordinates of Cebu

x2 = float(input("enter x2: "))

y2 = float(input("enter y2: "))

## Step 4: Compute the distance using the distance formula
d=math.sqrt(math.pow(x2 - x1 ,2)+math.pow(y2 - y1, 2))

## Step 5: Display the result rounded to two decimal places
print(f"The distance between Manila and cebu is: (distance:.2f)"

##Author
Capate, Jhasmine Gwynth S.
8-Molave
