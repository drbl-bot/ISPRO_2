# geometric_lib
'''
Library provides functions for calculating an area and perimeter of 
such figures as triangle, circle, rectangle and square;
'''

# Описание функционала
## circle.py
    - def area(r)
        r: int, float;
        return: int, float;
        - example: area(5) --> 78.53982

    - def perimeter(r)
        r: int, float;
        return: int, float;
        - example: perimeter(5) --> 31.41593
    
    

## square.py
    - def area(a)
        a: int, float;
        return: int, float;
        - example: area(5) --> 25

    - def perimeter(a)
        a: int, float;
        return: int, float;
        - example: perimeter(5) --> 20

## triangle.py
    - def area(a, h)
        a, h: int, float;
        return: int, float;
        - example: area(5, 5) --> 12.5

    - def perimeter(a, b, c)
        a, b, c: int, float;
        return: int, float;
        - example: perimeter(5, 5, 5) --> 15

## rectangle.py
    - def area(a, b)
        a, b: int, float;
        return: int, float;
        - example: area(5, 5) --> 25

    - def perimeter(a, b)
        a, b: int, float;
        return: int, float;
        - example: perimeter(5, 5) --> 20

# Logs of commits
```
    468e58d (HEAD -> new_features_467491) added comments to funcs
    cd2a2fc problem in rectangle solved; added triangle
    4893622 rectangle.py added
    86edb1c (origin/release) L-05: Update Docs. Add user agreement info
    438b89a L-05: Add user agreement
    6adb962 L-03: Docs added
    3049431 (origin/feature) L-04: Add rectangle.py
    b5b0fae (origin/develop) L-04: Update docs for calculate.py
    d76db2a L-04: Add calculate.py
    51c40eb L-04: Doc updated for triangle
    d080c78 L-04: Triangle added
    d078c8d (origin/main, origin/HEAD, main) L-03: Docs added
    8ba9aeb L-03: Circle and square added
```