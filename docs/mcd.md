role : code_role, name, slug
IS, 1N user, 11 role

In terms of, 1N recipe, 1N user, 11 role : autorisation
user : code_user, email, password, firstname, lastname

recipe : code_recipe, ingredients, preparation_time, cooking_time, title, picture, instructions
see, /1N user, 1N category, 1N recipe

relation, 1N recipe, 11 category : 1 recette dans ++ category.
category : code_category, name, picture, slug