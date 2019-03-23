---
title: Introduction
description: 'Who are you?'
---

## Welcome to Python!

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

Welcome to Pokem-- Python! My name is Matt! Some people call me Matthew, Widjaja, Wijaya, Widji, Widjuju... ahh forget it.

According to StackOverflow, Python is the top 3rd most popular & most loved programming language. And according to the Python Foundation, out of all Python users:
- 58% use it for Data Analysis
- 43% use it for DevOps/Automation
- 38% use it for Machine Learning

But, how do we get started? Well fortunately, I too have went on an adventure when I was a young lad, and it was to become the very best Pokemon Trainer in all the lands! And I did it all with Python and using it to explore the code of the game Pokemon Red/Blue _(ignore how Python wasn't on a Game Boy back in the 90s)_. 

So let's begin! I'll teach you & you'll teach me Poke-- Python.

`@instructions`
What's your name? The default is Ash but feel free to make it whatever you want.

`@hint`


`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
player_name = 'Ash'
```

`@solution`
```{python}
player_name = 'Ash'
```

`@sct`
```{python}
Ex().check_object('player_name').is_instance(str, not_instance_msg="player_name is not a string. Did you delete the around the player's name?")
success_message("Nice work {}, let's continue!".format(player_name))

```
