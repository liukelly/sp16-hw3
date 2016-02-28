1. What is the difference between new and create for a model?
`new` will create the object but will not store it in to the database so it is
not persistent so you would have to run `<variable obj>.save!`. However,
`create` will.

2. What command combined with new will emulate the same behavior as create?
`<variable obj>.save!`.

3. What is the column that exists on every table but we did NOT define?
`id`, `created_at`, and `updated_at`.

4. What single line of ruby code can insert a cat with the name "hat" in the
   database?
`Cat.create name:"hat"`

5. What was the most confusing part over the last few weeks?
Instructions on homework could be more clear, or references to useful links /
guides / slide number would be cool! But there's no significant issues.

6. How did you like this homework in comparison with the others?
It was pretty chill!
