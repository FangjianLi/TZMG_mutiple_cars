## TZMG learning for safe driving policy

The TZMG framework is used to train a safe driving policy under the maximum uncertainties of neighbor vehicles. This training framework can output the driving policies of both subject car (safe) and neighbor vehicles (adversarial). Moreover, the TZMG framework can help to exploit the corner cases in autonmous driving in automatically. The codes will be uploaded soon. The corresponding paper has been accepted and to be presented at ACC 2023. 



## Results
The trained safe driving policy is compared with vanilla RL policy PPO. As can be seen, the safe driving policy trained in TZMG framework has much better peformance in dealing with adversarial vehicles. 

<p>
    <img src="carla_simulator.gif" width="600"/>
    <em>3D simulator (green car is controlled by human with keyboard, and yellow car is controlled by trained driving policy)</em>
</p>
