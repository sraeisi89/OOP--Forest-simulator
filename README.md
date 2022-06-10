# OOP--Forest-simulator
You are going to model a Forest with rain and a lumberjack who cuts tall trees

Tree
Trees should have a height.
We should be able to create trees in two ways:
providing height
not providing height, in this case the height will be 0 by default.
It has an irrigate method which will increase the height of the tree. The implementation should depend on the type of the tree.
It has a getHeight method which returns the tree's height.
WhitebarkPine
This tree type grows by 2 units each time its irrigated.
FoxtailPine
This tree type grows by 1 unit each time its irrigated.
Lumberjack
You should be able to create a lumberjack without providing any parameters.

It has a canCut(tree) method which takes a tree as parameter and returns true if its taller than 4 units.
Forest
The Forest has Trees.
We should be able to create a forest by providing a list of trees.
It should have a getTrees() method returning every Tree in the Forest.
It has a rain() method which should irrigate every Tree in the Forest.
It has a cutTrees(lumberjack) which should remove all the trees which can be cut by the lumberjack. (It calls the canCut method on the lumberjack).
It has an isEmpty method which returns true if there is no tree in the forest.
It has a getStatus method which returns an array/list with status reports about each tree in the forest. For example:
[
  'There is a 3 tall WhitebarkPine in the forest.',
  'There is a 2 tall WhitebarkPine in the forest.',
  'There is a 4 tall FoxtailPine in the forest.'
]
