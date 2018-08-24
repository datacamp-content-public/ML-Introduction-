---
title: Test
description: Test
---

## An exercise title written in sentence case

```yaml
type: NormalExercise 
lang: python
xp: 100 
skills: 2
key: 4333de8b9f   
```


This is the assignment text. It should help provide students with the background information needed.
The instructions that follow should be in bullet point form with clear guidance for what is expected.


`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`

```{python}
import numpy as np
```


`@sample_code`

```{python}
x=[1,2,3,4]
# write code to create an np.array from x
```


`@solution`

```{python}
x=[1,2,3,4]
a=np.array(x)
```


`@sct`

```{python}
# Update this to something more informative.
success_msg("Use np.array method")
```


