﻿Chef and Recipe
https://www.codechef.com/COOK118B/problems/CHEFRECP


In Chefland, types of ingredients are represented by integers and recipes are represented by sequences of ingredients that are used when cooking. One day, Chef found a recipe represented by a sequence A1,A2,…,AN at his front door and he is wondering if this recipe was prepared by him.
Chef is a very picky person. He uses one ingredient jar for each type of ingredient and when he stops using a jar, he does not want to use it again later while preparing the same recipe, so ingredients of each type (which is used in his recipe) always appear as a contiguous subsequence. Chef is innovative, too, so he makes sure that in each of his recipes, the quantity of each ingredient (i.e. the number of occurrences of this type of ingredient) is unique ― distinct from the quantities of all other ingredients.
Determine whether Chef could have prepared the given recipe.
Example
Input
3
6
1 1 4 2 2 2
8
1 1 4 3 4 7 7 7
8
1 7 7 3 3 4 4 4
Output
YES
NO
NO
