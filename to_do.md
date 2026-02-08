# Restructure
## Lessons learned
- NEVER copy paste from R visual editor to github editor. Make a sticky note.
- conflicts_prefer(palmerpenguins::penguins)
-- This is the standard. The penguins in dfferent pakages (here 3) could be different say with different column names. But it is important to be **specific**. I must take care of such specificities.
-- This is basically saying that I am just a beginner!!! 
## Yes or No
- [y] Core packages are give all at one - may cause concern within the noob community.
- [y]May be the packages lising parsnip ... rsample be moved to the end?
-- Done. rsample is introduced in the real workflow in the end.

- [y] I think recipe should be introduced first.
-- Done but in Building blocks.

- [n] Add examples for recipe?
-- The students may be asked to test different models say in parsnip. So no need to give extra examples.
## Guiding light
- And one model at a time! This is the tidymodel philosophy!!!
