 Test Plan
-------------------------------------------------------------------------------------

A test plan is a detailed document which describes software testing areas and activities. It outlines the test strategy, objectives, test schedule, required resources (human resources, software, and hardware), test estimation and test deliverables.
The test plan is a base of every software's testing. 
It is the most crucial activity which ensures availability of all the lists of planned activities in an appropriate sequence.


### Table no: High level test plan
| Test ID |           Description       |      Exp I/P    |    Exp O/P   |   Actual Out  | Type of Test      |
| --------| --------------------------  | --------------- | ------------ | ------------- | --------------    |
|  H_01   | Start the game              | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_02   |    Player1                  | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_03   |    Player2                  | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_04   |    Snakes                   | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_05  |    Ladders                   | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_06  |    Game Over                 | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |
|  H_07   |    Exit                     | Choice          |  SUCCESS     |  SUCCESS      | Reqirement based  |

### Table no: Low level test plan
| Test ID |           Description       |      Exp I/P    |    Exp O/P   |   Actual Out  |  Pass or Fail  |
| --------| --------------------------- | --------------- | ------------ | ------------- | -------------- |
|  L_01   |  Display Data               |   Success       | Success      |  Success      |  Pass          |
|  L_02   |  Sore Player1               |   Winner        |  Winner      |  Runner       |  Fail          |
|  L_03   |  Score Player2              |   Runner        |  Runner      |  Winner       |  Fail          |
