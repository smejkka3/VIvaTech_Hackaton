# VivaTech_Hackaton

Deep learning classifier of car images using pre-trained model that can label the image with: "not car", "good car", "low damaged car" and "highly damaged car" for usage in the G-Scan APP. Proof of concept for VivaTech hackathon.


## Examples:
[videoexample](https://www.youtube.com/watch?v=gcKHIUg8Dbs)

![notdamaged](https://user-images.githubusercontent.com/7142404/40572881-9fa7e468-60b7-11e8-9f30-f3a5c06c0423.jpg)
output: This is not a damaged car with confidence 49.16%.

![low_damaged](https://user-images.githubusercontent.com/7142404/40572876-7e1e1d9e-60b7-11e8-9930-0efcf40deeae.jpg)
output: This is a low damaged car with 64.99% confidence.

![high_damaged](https://user-images.githubusercontent.com/7142404/40572891-bb24b496-60b7-11e8-9f0e-504bbbc61a80.jpg)
output: This is a high damaged car with 67.55% confidence.

![horse](https://user-images.githubusercontent.com/7142404/40572904-eaccc418-60b7-11e8-897c-cba96aa859b5.jpg)
output: This is not the image of a car with confidence 69.73%.

## Requisites:
python
tensorflow - pip install tensorflow


## Usage:
python classifier.py "path_to_image"

## References:
https://github.com/raviranjan0309/Car-Damage-Detector
