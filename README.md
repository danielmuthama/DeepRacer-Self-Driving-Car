#### REINFORCEMENT LEARNING

### DeepRacer-Self-Driving-Car

#### Note: The model contains large data you need to:

      install:
      git lfs install
      git lfs track "*{.largefile}"
      git add .
      .....

[<img src="https://github.com/danielmuthama/DeepRacer-Self-Driving-Car/blob/main/soi.png?raw=true" width="90%">](https://www.youtube.com/watch?v=ALcvOg81huE "AWS DeepRacer: 55")
#### Before you start

In this tutorial, you will train a reinforcement learning (RL) model and see a simulation of how that model performs on a track. The AWS DeepRacer Student League is where you compete for the fastest lap times with you friends. You have the option to opt out of submitting your trained model to the Student League.
#### How is an RL model trained?

In AWS DeepRacer, an agent (car) learns from an environment (track) by interacting with it. During training, the model iterates and updates different parameters based on rewards received.
Model training is an iterative process

Training a model is like creating a prototype. Each model iteration is a step towards finding the optimal parameters. When training has finished, clone your model to continue improving it.
#### Improving your model

After training an initial model, you can use the current state of the model's parameters as the starting point for the next model by choosing clone model. Submit to the leaderboard to evaluate your model's performance. Look for the race time and the number of times your car went off track.
#### Simulation video stream

Just like babies learn to walk by stumbling around, your model learns by trial and error. In reinforcement learning, this is called exploration and exploitation. Your AWS DeepRacer car explores the racetrack gathering information about its environment and then exploits that information to maximize it’s reward.

For the first iterations, the model might hit walls or go off track, but slowly the model learns what actions give it the highest reward and it starts to improve..

When your model has finished training, it is automatically submitted to the AWS DeepRacer Student League leaderboard if you did not opt-out during the model training tutorial.
