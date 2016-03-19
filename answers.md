# Q0: Why is this error being thrown?

# There is no Pokemon controller or model set up yet.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

# The random Pokemon are appearing because the database was seeded with Pokemon found in the seeds.rb file. None of these Pokemon have a trainer when seeded.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

# This line creates a button that allows the currently logged-in user to 'capture the Pokemon', which means that the capture_path function was called on the current Pokemon's id. Additionally, the Pokemon's id is assigned to the currently logged-in trainers' id.

# Question 3: What would you name your own Pokemon?

# lolmon

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

# A path back to the current trainer.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

# When the Pokemon that is being created is unable to be saved into the database, then this line will show the "@pokemon.errors.full_messages.to_sentence".

# Give us feedback on the project and decal below!

# I really enjoyed this project! I felt like I could finally put together everything that I learned in class so far. The decal is also really cool, and the material that is being presented is very thoroughly explained and straightforward.

# Extra credit: Link your Heroku deployed app
