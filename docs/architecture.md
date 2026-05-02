# System Architecture

The system follows a learning-from-demonstration pipeline.

## Components:

1. Leader Arm → captures human motion
2. Follower Arm → executes motion
3. Camera → captures environment
4. Dataset → stores motion + vision data
5. Model → trained using imitation learning
6. Inference Engine → executes learned task

## Pipeline Flow:

Human → Leader Arm → Dataset → Training → Model → Robot Execution
