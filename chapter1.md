---
title: 'Pallet + Viridian Town'
description: 'We''ll get you onboarded onto Python, show you some editors you can use on your local machine, and get you spun up on some variables.'
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
success_msg("Nice work, let's continue!")

```

---

## Choose your Starter Editor

```yaml
type: PureMultipleChoiceExercise
key: a8f4aa6f0d
xp: 50
```

Professor Oak stopped me as I was about to leave the city, saying it's too dangerous out there without a way to edit Python code! And he was right, while we are here in DataCamp and its spiffy console, we will switch away from it later on in the gam- course.

# First, download Anaconda
You must download Anaconda, which is 'normal' Python plus a bunch of packages we will need. Install it from **https://anaconda.com/distribution**.

**Be sure to download the Python 3 version** -- Python 2 will be discontinued in 2020.

# Speaking of fun editor options...
These are not the only options by far. Many people have their own favorite IDEs such as PyCharm or Visual Studio too. But I wanted to provide 3 options to mirror Poke-, I mean, to start easy.

**Option 1: JupyterLab**
- Good for data exploration
- Hard to share or reuse code
- Can't debug code step-by-step
- To use it, launch the program 'Anaconda Navigator', and then click on 'JupyterLab'. Then, click on 'Notebook'

**Option 2: Spyder**
- Good for introductory code development
- More clunky for data exploration.
- Slightly Heavy Weight
- To use it, launch the program 'Anaconda Navigator', and then click on 'Spyder'.

**Option 3: Text Editor + Terminal**
- Well, using a terminal or command prompt is in your future.
- Gives you greatest flexibility in debugging & editing code.



`@hint`
Don't worry, this won't be a choose your own adventure book.

`@possible_answers`
- [Let's do this]

`@feedback`
