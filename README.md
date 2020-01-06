# Pouring-problem

1. Pouring problem: X and Y are the capacity of glasses; (x, y) is current fill levels and represents a state. The goal is a level that can be in either glass. Start at start state and follow successors until we reach the goal. Keep track of frontier and previously explored; fail when no frontier.

Return a dict of {state:action} pairs describing what can be reached from the (x, y) state, and how.

2. More pour problem: In this problem, you will solve the pouring problem for an arbitrary number of glasses. Write a function, more_pour_problem, that takes as input capacities, goal, and (optionally) start. This function should return a path of states and actions. Capacities is a tuple of numbers, where each number represents the volume of a glass. Goal is the desired volume and start is a tuple of the starting levels in each glass. Start defaults to None (all glasses empty). The returned path should look like [state, action, state, action, ... ] where state is a tuple of volumes and action is one of ('fill', i), ('empty', i), ('pour', i, j) where i and j are indices indicating the glass number. 

The first argument is a tuple of capacities (numbers) of glasses; the goal is a number which we must achieve in some glass.  start is a tuple of starting levels for each glass; if None, that means 0 for all. Start at start state and follow successors until we reach the goal. Keep track of frontier and previously explored; fail when no frontier. On success return a path: a [state, action, state2, ...] list, where an action is one of ('fill', i), ('empty', i), ('pour', i, j), where i and j are indices indicating the glass number."""
