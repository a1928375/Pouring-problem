# Pouring-problem

X and Y are the capacity of glasses; (x, y) is current fill levels and represents a state. The goal is a level that can be in either glass. Start at start state and follow successors until we reach the goal. Keep track of frontier and previously explored; fail when no frontier.

Return a dict of {state:action} pairs describing what can be reached from the (x, y) state, and how.
