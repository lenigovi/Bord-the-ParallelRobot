**By [Elena Valerija Herzegovina](https://github.com/lenigovi)**

This repository contains the implementation of the report:

![alt text][robot]

[robot]: https://github.com/lenigovi/ParallelRobot/blob/main/Robot.png "Robot"


![alt text][robotcad]

[robotcad]: https://github.com/lenigovi/ParallelRobot/blob/main/Robotcad.png "Cad Model"






Citation:
```bibtex
@inproceedings{Herzegovina2023,
 author    = {Herzegovina, Elena Valerija},
 title     = { },
 booktitle = { },
 year      = {2023}}
```





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      font-family: 'Arial', sans-serif;
    }
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .box {
      border: 2px solid #333;
      border-radius: 5px;
      padding: 10px;
      margin: 10px;
      text-align: center;
    }
    .arrow {
      width: 0; 
      height: 0; 
      border-left: 15px solid transparent;
      border-right: 15px solid transparent;
    }
    .arrow-up {
      border-bottom: 15px solid #333;
      margin: auto;
    }

    .arrow-down {
      border-top: 15px solid #333;
      margin: auto;
    }
  </style>
  <title>Parallel Robot Architecture</title>
</head>
<body>
  <div class="container">
    <div class="box">
      <p>User Interface</p>
    </div>
    <div class="arrow arrow-up"></div>
    <div class="box">
      <p>Controller Board<br/>(Microcontroller)</p>
    </div>
    <div class="arrow arrow-up"></div>
    <div class="box">
      <p>Kinematics Solver<br/>(Inverse Kinematics)</p>
    </div>
    <div class="arrow arrow-up"></div>
    <div class="box">
      <p>Motor Controllers<br/>(Servo Motor Drivers)</p>
    </div>
    <div class="arrow arrow-up"></div>
    <div class="box">
      <p>Parallel Robot<br/>(Mechanical Structure)</p>
    </div>
    <div class="arrow arrow-up"></div>
    <div class="box">
      <p>End-Effector<br/>(Tool or Payload)</p>
    </div>
  </div>
</body>
</html>
