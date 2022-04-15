# SIT-215-Fuzzy_Car_Project

## File structure

- **csv_data**
-- data we used to adjust our rules
- **fis**
-- fuzzy model created using MATLAB
- imgs
-- example plot to show our result
- demo
-- video demo from our enviroment simulator
- report
-- report for our group.
- presentation
-- our presentation recording

## How to run the enviroment simluator
### Method 1:
Open the main.py using vscode and start debuging.

### Method 2

Using terminal and type
```
python main.py
```

### Change Speed
To change the initial speed of the vehicle, go to env_simulator.py
```python
#change the speed from 100.0 to other speed.
self.vehicles.append(self.Vehicle(100.0, {'x': 0, 'y': 500}))
```

### Change System Activate Distance
The fuzzy logic for break pressure only activated with in certain distance, 100m by default.
To change that, go to env_simulator.py and change the constance

```python
CAS_TRIGGER_DISTANCE = 100 # 100m
```
