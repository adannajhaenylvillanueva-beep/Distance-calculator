# Distance-calculator
import math


class DistanceCalculator:
    """Calculates the distance between two points."""

    def calculate_distance(self, x1, y1, x2, y2):
        """Return the distance between two points using the distance formula."""
        horizontal_distance = x2 - x1
        vertical_distance = y2 - y1

        distance = math.sqrt(
            horizontal_distance ** 2 + vertical_distance ** 2
        )

        return distance


# Create a distance calculator.
calculator = DistanceCalculator()

# Coordinates of the two points.
x1 = 2
y1 = 3
x2 = 8
y2 = 7

# Calculate and display the distance.
distance = calculator.calculate_distance(x1, y1, x2, y2)

print(f"Distance between the two points: {distance:.2f}"

## Sample Output
Distance between the two points: 7.21
