# Weather_App
Python CLI tool using API to show the weather of regions.

## Features:
- Weather check by entering city names
- Weather check by entering latitude and longitude of regions
- Showing coord, weather, weather description, temperature, feel-like temperature, pressure, humidity, and name of the region

## Skills Practiced:
- API Integration
- HTTP Error Handling
- Environment Variable
- Query Parameter Handling
- Function Design

## Takeaways
- Should differently handle HTTP errors based on their types. Some types, such as 400 or 404, can be fixed by retrying, but some others, such as 401 or 5xx, might not be fixed by just retrying. Error handling should check difference in errors.
- In Python, "if x == a or b or c" is not equal to "x is a, b, or c." Each "or" term is evaluated independently. Should use "if x in (a,b,c)" to check the "x is a, b, or c" condition.
