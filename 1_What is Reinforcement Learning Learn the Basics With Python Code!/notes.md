# Why Reinforced Learning

# We want to use ML to come up with solutions to problems
# To be able to solve our problems with ML we need to frame our problems in terms of some "cost" or "loss" that we want to minimize
# We need to know how to update our ML system in order to minimize the loss
    # What fo we do if we don't know how to update our system in order to minimize the cost

# Example of RL problem
    # Pick and Place with robot arm

# Reinforced Learning Framework
    # It's made up of the following:
        # Environment: The medius in which we wish to interact with, e.g. power plant/factory.
        # Observation/State: Any information extracted from the environment at the current timestamp, e.g sensor data.
        # Agent: The thing acting in the environmnet, e.g. robot        
        # Task/Goal: What we want the agent to do in the environment e.g. stack blocks with a robot arm.        
        # Reward: The mean by which we encourage certain actions/behaivor in certain states, e.g. penalty.
        
        # Policy: How we decide what action
        # Value: How "good" is our current situation

    # Trajectory: A single interaction in our environment
    # Terminal State: Final state
        