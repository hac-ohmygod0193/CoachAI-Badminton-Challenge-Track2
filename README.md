# CoachAI-Badminton-Challenge-Task-2

## overview
This is a model for predicting badminton strokes. The input contains the information of first 4 strokes of each rally, and there would be (rally_length - 4) predicted strokes as the output.

## prerequisite

### coding environment
Google Colab (Python 3.10.12)
### packages version
Check requirements.txt for more informations.


## usage
- Train
```
!python train.py --model_type {model_type}
```
* Evaluate
```
!python generator.py {model_path}
```
## hyperparameters
- model_type
- batch_size
- epochs

## experiment results
Score sheet: 
https://docs.google.com/spreadsheets/d/15EogJ0XS6cmDzooSyDhwsRabHgcsqgoPACAvdR9ZHps/edit#gid=0
