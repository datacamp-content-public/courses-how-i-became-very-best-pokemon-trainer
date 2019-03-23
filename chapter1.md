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

According to StackOverflow, Python is the top 3rd most popular & most loved programming language. But, how do we get started? Well fortunately, I too have went on an adventure when I was a young lad, and it was to become the very best Pokemon Trainer in all the lands! And I did it all with Python and using it to explore the code of the game Pokemon Red/Blue _(ignore how Python wasn't on a Game Boy back in the 90s)_.

This class assumes that you're familiar with another programming language already but feel free to give this class a try even if you don't!

So let's begin! I'll teach you & you'll teach me Poke-- Python.

`@instructions`
player_name is a variable right now that's set to my name, Matt. Change it to your name and then click the green 'Submit Answer' button to go to the next part of this course.

`@hint`
Don't delete the quotes around the current name! We'll talk about variable syntax later, but those two quotes are vital to the name.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
player_name = 'Matt'
```

`@solution`
```{python}
player_name = 'Matt'
```

`@sct`
```{python}
Ex().check_object('player_name').is_instance(str, not_instance_msg="player_name is not a string. Did you delete the around the player's name?")
success_msg("Nice work {}, let's continue!".format(player_name))

```
