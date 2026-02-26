# Robot Classification using UCI HAR Dataset

## Aim
To analyze motion sensor data and classify robot types using rule-based classification.

## Algorithm
1. Load motion dataset
2. Extract velocity feature
3. Extract altitude proxy
4. Apply rules:
   If altitude > threshold → Aerial Robot
   Else if velocity > threshold → Ground Robot
   Else → Stationary Robot
5. Display result

## Output
Aerial Autonomous Robot

## Tools Used
Python
Google Colab
GitHub
