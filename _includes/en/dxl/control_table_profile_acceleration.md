
If Velocity-based Profile is selected for Drive Mode(10), Profile Acceleration(108) sets acceleration of the Profile.  
If Time-based Profile is selected for Drive Mode(10), Profile Acceleration(108) sets accelerating time of the Profile.  
Profile Acceleration(108) is applied in all control mode except Current Control Mode.  
Please refer to [Profile Velocity(112)](#profile-velocity112) for more details.

| Velocity-based Profile |            Values             | Description                             |
|:----------------------:|:-----------------------------:|:----------------------------------------|
|          Unit          | 214.577 [rev/min<sup>2</sup>] | Sets acceleration of the Profile        |
|         Range          |           0 ~ 32767           | '0' stands for an infinite acceleration |

| Time-based Profile |  Values   | Description                                                                                                                                |
|:------------------:|:---------:|:-------------------------------------------------------------------------------------------------------------------------------------------|
|        Unit        | 1 [msec]  | Sets accelerating time of the Profile                                                                                                      |
|       Range        | 0 ~ 32737 | '0' stands for an infinite accelerating time('0 [msec]').<br>Profile Acceleration(108) will not exceed 50% of Profile Velocity(112) value. |
