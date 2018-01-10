# Useful Math

## Distance between two points
## 2D
> Method #1 (Using hypotenuse):

    distance = hypot(x1 - x2, y1 - y2);

> Method #2 (Using square root):

    float a = x1 - x2
    float b = y1 - y2

    float distance = sqrt(a*a + b*b);

## Angle between two points
## 2D
> Method #1 (Using atan2):

    float angle = atan2(y1 - y2, x1 - x2) * (180/M_PI) - 90;
