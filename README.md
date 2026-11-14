# grid_world_agent
Practice notebooks for computational neuroscience: a spiking neuron model, and a Q-learning agent in a grid world that relearns when its goal moves. Built while learning how a brain could form a general rule from experience.
# Grid world agent
A 5x5 room where an agent learns, by trial and error (Q-learning), to reach a goal.
After it learns, I move the goal to a new corner and watch it relearn.

What I found:
- The agent first needs many steps, then settles to the shortest path (8 steps).
- When the goal moves, it gets lost for a while, because the old knowledge pulls it the wrong way.
- It relearns only the squares it walks through, so some arrows on the map still point to the old goal.

This is a simple version of the question: how can a brain learn a general rule, so that one new experience updates everything at once?
