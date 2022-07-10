REINFORCEMENT LEARNING
### DeepRacer-Self-Driving-Car

#### Note: The model contains large data you need to:

      install:
      git lfs install
      git lfs track "*{.largefile}"
      git add .
      .....
<video src="model.mp4" controls="controls" style="max-width: 730px;">
</video>

#### Simulation video stream

Your are watching your model train in a live simulation of the racetrack you selected.

Just like babies learn to walk by stumbling around, your model learns by trial and error. In reinforcement learning, this is called exploration and exploitation. Your AWS DeepRacer car explores the racetrack gathering information about its environment and then exploits that information to maximize it’s reward.

For the first iterations, the model might hit walls or go off track, but slowly the model learns what actions give it the highest reward and it starts to improve..

When your model has finished training, it is automatically submitted to the AWS DeepRacer Student League leaderboard if you did not opt-out during the model training tutorial.
