# Assessment of Reward Functions for Reinforcement Learning Vehicular Traffic Signal Control Under Real-World Limitations

## Submitted to IEEE Systems, Man and Cybernetics 2020

Adaptive traffic signal control is one key avenue for mitigating the growing consequences of traffic congestion.
Incumbent solutions such as SCOOT and SCATS require regular and time-consuming calibration, can’t optimise well for multiple road use modalities, and require the manual curation of many implementation plans.

Vision-based traffic sensors, such as those from Vivacity Labs, as well as advances in GPU technology, have paved the way for real-time machine learning approaches in this field, with deep reinforcement learning showing promising results. 
This uses deep neural networks to choose the best action in any given state, but is sensitive to the choice of reward function. 
Several authors have surveyed the reward functions used in the literature, but attributing outcome differences to reward function choice across works is problematic as there are many uncontrolled differences, as well as different outcome metrics.

This paper compares reward functions in a simulation of a junction in Greater Manchester, UK, across various demand profiles, subject to real world constraints: realistic sensor inputs, controllers, calibrated demand, intergreen times and stage sequencing. 
The reward metrics considered are based on the time spent stopped, lost time, change in lost time, average speed, queue length, junction throughput and variations of these magnitudes.
The performance of these reward functions is compared in terms of total waiting time.
We find that speed maximisation resulted in the lowest average waiting times across all demand levels, displaying significantly better performance than other rewards previously introduced in the literature.

<object data="https://github.com/ACabrejas/SMC2020_Reward_Functions_RL_UTC/blob/master/conference_101719.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/ACabrejas/SMC2020_Reward_Functions_RL_UTC/blob/master/conference_101719.pdf">
        <p>This browser does not support displaying PDFs here. Please go to the location of the full PDF to view it: <a href="https://github.com/ACabrejas/SMC2020_Reward_Functions_RL_UTC/blob/master/conference_101719.pdf">View PDF</a>.</p>
    </embed>
</object>
