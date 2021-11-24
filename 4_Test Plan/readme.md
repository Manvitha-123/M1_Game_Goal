 Test Plan
-------------------------------------------------------------------------------------

A test plan is a detailed document which describes software testing areas and activities. It outlines the test strategy, objectives, test schedule, required resources (human resources, software, and hardware), test estimation and test deliverables.
The test plan is a base of every software's testing. 
It is the most crucial activity which ensures availability of all the lists of planned activities in an appropriate sequence.


### Table no: High level test plan
| Test ID |           Description       |      Exp I/P    |    Exp O/P   |   Actual Out  | Pass or Fail   |
| --------| --------------------------  | --------------- | ------------ | ------------- | -------------- |
|  H_01   | Start the game              | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_02   |    Player1                  | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_03   |    Player2                  | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_03   |    Snakes                   | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_03   |    Ladders                  | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_03   |    Game Over                | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |
|  H_03   |    Exit                     | SUCCESS         |  SUCCESS     |  SUCCESS      |  Pass          |

### Table no: Low level test plan
| Test ID |           Description       |      Exp I/P    |    Exp O/P   |   Actual Out  |  Pass or Fail  |
| --------| --------------------------- | --------------- | ------------ | ------------- | -------------- |
|  L_01   |  Display Data               |   Success       | Success      |  Success      |  Pass          |
|  L_02   |  Sore Player1               |   Winner        |  Winner      |  Runner       |  Fail          |
|  L_03   |  Score Player2              |   Runner        |  Runner      |  Winner       |  Fail          |
