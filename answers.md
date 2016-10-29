# Q0: Why is this error being thrown?
we never created a pokemon object

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
we use the .sample method to randomly select a pokemon
common factor is that they are all the ones we own rn

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
it calls the patch method that routes to our capture method

# Question 3: What would you name your own Pokemon?
Poseidon

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
a path name
the path needed a trainer id

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
we access the flash hash and display the errors part of it

# Give us feedback on the project and decal below!
it was coo
# Extra credit: Link your Heroku deployed app
