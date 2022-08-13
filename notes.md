* It is not so bad to refactor a class method to be a pure function. 
delete all references to `self.` and the relevant variables should highlight themselves in red.
  * The reason you might use something like Equinox is because maybe the class attributes are separate for the purpose of doing a gradient descent over. It is about having a certain representation of the `Pytree` that is easy to work with.
* Don't try to write some book that has "incredible pedagogy and diagrams" or something.
  *   Do not worry about the pedagogy, the pedagogy is owned by academics, not you. 
  *   Publish materials that are for experts to read.
