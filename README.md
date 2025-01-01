# Haskell Undefined Function or Missing Import

This repository demonstrates a common error in Haskell programming: using a function that hasn't been imported or defined in the current scope. The `bug.hs` file contains the erroneous code, while `bugSolution.hs` provides the corrected version.

## Problem

The code attempts to use a function without importing the necessary module or defining the function locally. This leads to a compilation error.

## Solution

The solution involves either importing the required module using `import` or defining the function within the current scope.