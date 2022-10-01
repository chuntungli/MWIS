# MWIS
Implementation of a maximum weighted independent set algorithm for weighted graph

Example:
# V = [0, 1, 2, 3, 4, 5]
# E = [(0,1), (0,2), (2,4), (4,5)]

weights = np.array([0.5, 1, 2, 0.5, 1, 0.7])
adjacency = np.array([[1,2], [], [4], [], [5], []])

solution = MWIS(weights, adjacency)
