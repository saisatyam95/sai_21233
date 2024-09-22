**Q1: TSP**

*Dynamic Programming Results:*

Episode 0 Q-values:

[[-1000. -1000. -1000. ... 0. 0. 0.]
 [-1000. 0. 0. ... 0. 0. 0.]
 [-1000. 0. 0. ... 0. 0. 0.]
 ...
 [0. 0. 0. ... 0. 0. 0.]
 [0. 0. 0. ... 0. 0. 0.]
 [0. 0. 0. ... 0. 0. 0.]]
 
Episode 200, Q-values: 

[[-6793.4652093 -6531.994 -6472.945 ... -6472.945 -6413.2399 -6424.45921]
 [-4463.304139 -3940.399 -3699.1 ... -3940.399 -3941.0551 -3947.6161]
 [-3262.429 -3940.399 -3940.399 ... -3940.399 -3940.399 -2977.39]
 ...
 [-3262.429 -3940.399 -3940.399 ... -3940.399 -2978.119 -2992.699]
 [-3328.039 -3940.399 -3940.399 ... -3940.399 -3940.399 -2977.39]
 [-3526.9831 -3940.399 -3940.399 ... -3211.399 -3940.399 -3940.399]]


 
Episode 400, Q-values: 

[[-10466.17457413 -10361.73891851 -10884.14411374 ... -10845.05501357
  -10810.54428516 -10694.0444474 ]
 [ -6889.68786362  -7725.53055721  -7322.31378696 ...  -7728.99581825
   -6799.73089869  -6812.80275297]
 [ -6904.55811424  -7725.43489783  -7725.53055721 ...  -7728.47671784
   -6805.73448138  -6836.99075333]
 ...
 [ -6933.79927352  -7713.63244352  -7721.28052144 ...  -7725.53055721
   -6806.93405001  -6863.24442234]
 [ -6962.92516324  -7712.9685196   -7725.53055721 ...  -7725.83752338
   -7725.53055721  -6815.01444566]
 [ -7278.29846159  -7725.32967251  -7725.79447665 ...  -7234.65827511
   -7725.57446486  -7725.53055721]]


   
Episode 600, Q-values: 

[[-14854.22289051 -14311.58512717 -14205.57631828 ... -14691.31684946
  -14666.22994309 -14549.74563625]
 [-10596.81045624 -11361.51282839 -10825.47192451 ... -10469.33635023
  -10474.85626386 -10496.42870328]
 [-10613.39336031 -11360.04024455 -11361.51282839 ... -10494.60640867
  -10506.7899048  -10533.51191622]
 ...
 [-10621.35842504 -11289.03484814 -11305.86893024 ... -11361.51282839
  -10475.77463044 -10520.36467072]
 [-10661.40026464 -11317.82974263 -11343.76959714 ... -10467.20578625
  -11361.51282839 -10498.57748489]
 [-11004.78231203 -11350.64112627 -11361.69201036 ... -11030.93382181
  -11361.5416362  -11361.51282839]]


  
Episode 800, Q-values:

 [[-18209.30624028 -17890.4327922  -17713.11764249 ... -17697.77755588
  -18170.91172228 -18075.41007239]
 [-14224.28997544 -14854.22289051 -14247.26604955 ... -14002.03167754
  -14014.3015724  -14035.70087136]
 [-14255.20161539 -14852.65136842 -14854.22289051 ... -14053.75364469
  -14110.34424406 -14121.12696413]
 ...
 [-14270.89644571 -14770.75337587 -14814.96162155 ... -14854.22289051
  -14003.67543771 -14042.62595608]
 [-14305.30722072 -14801.08400674 -14818.72470667 ... -13995.28744208
  -14854.22289051 -14021.89655409]
 [-14636.55372753 -14846.44313775 -13995.00629807 ... -14515.89870056
  -14854.25482489 -14854.22289051]]


  
Optimal Policy: [27 47 32  3 35 43 46 49 46 48 44 47 38 41 44 46 43 44 47 37 44 46 37 45
 42 45  2 42 47 46 44 46 42 43 49 42 43 44 34 48  1 43 10 18 31 29 38 36
 21 49]




*Monte Carlo Method:*


First Visit:

[first visit] Episode 0, Total reward: -450073.71245972626

[first visit] Episode 200, Total reward: -370162.94211850595

[first visit] Episode 400, Total reward: -340181.72428274265

[first visit] Episode 600, Total reward: -350232.7555967795

[first visit] Episode 800, Total reward: -310259.48477476713


Optimal Policy (First Visit): [ 0 40 30 43 39 25 35 13 39 32 14 39 43 46 23 34 37  6 35 48  8 49 39  5
 28 13  8 28 19 33 31 48 48  9 19 49 12 19 24  6  4 11 45  4 43 21  4 21
  4 16]


Every Visit:

[every visit] Episode 0, Total reward: -450077.99397766375

[every visit] Episode 200, Total reward: -270359.10190867144

[every visit] Episode 400, Total reward: -160558.9483436579

[every visit] Episode 600, Total reward: -220417.5350452337

[every visit] Episode 800, Total reward: -280311.3135306718

Optimal Policy (Every Visit): [34  9 34 46 47 42  4 21 27 24 39  8 48 27 22 17 30 48 12  8 14 18 26 31
  2 15 23 22 45 48 43 32 15  1 18 25 43  8 40 11 10  5 40 36  6 24 20  9
 16  3]



Dynamic Programming (DP) Methods: DP methods like Value Iteration and Policy Iteration calculate the value of each state by repeatedly applying the Bellman equation. These methods need a detailed understanding of the environment, including all possible state transitions and rewards. Because of this, they're best suited for simpler problems where everything about the environment is known and not too complex.


Monte Carlo (MC) Methods: MC methods work by observing what happens in many playthroughs or episodes and averaging the results to estimate how good different states or actions are. Unlike DP, MC methods don't require knowing all the details of the environment beforehand, making them more adaptable to complex situations where it's hard to predict what might happen next.



**Q2: Sokoban Puzzle**


Dynamic Programming Optimal Value Function for Sokoban: 

[[-6.89215401 -6.54683861 -6.16315475 -6.54683927 -6.89215534 -7.20293981]
 [-6.54683861 -6.16315475 -5.73683927 -6.16315534 -6.54683981 -6.89215583]
 [-6.16315475 -5.73683927 -5.26315534 -5.73683981 -6.16315583 -6.54684025]
 [-5.73683927 -5.26315534 -4.73683981 -5.26315583 -5.73684025 -6.16315622]
 [-5.26315534 -4.73683981 -5.26315583 -4.73684025 -5.26315622 -5.7368406 ]
 [-5.73683981 -5.26315583 -4.73684025 -5.26315622 -5.7368406  -6.16315654]
 [-6.16315583 -5.73684025 -5.26315622 -5.7368406  -6.16315654 -6.54684089]]



Monte Carlo Optimal Values for Sokoban: 

[[ -15.66508757  -21.49422492  -26.01879128  -27.61998026  -26.52493805
   -22.01504218]
 [ -16.19813204  -28.57280048  -42.25577283  -57.53933392  -44.38977701
   -31.58453973]
 [ -17.66562612  -29.74704684  -53.96128564 -101.80692488  -55.16170944
   -33.89258518]
 [ -11.54414164  -15.6320247   -20.92031342  -48.15871245  -39.32007447
   -24.55431133]
 [  -8.93448484   -8.01692992    0.          -18.44501244  -21.16250713
   -15.39466475]
 [  -6.13379704   -8.08514112   -6.096876    -10.09204615  -15.13271069
   -12.53768911]
 [  -3.37001771   -4.60460524   -5.72760526   -8.4259349    -9.79481231
    -9.34686409]]

