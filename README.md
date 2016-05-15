# fingers-game-ruby-
this code is a guessing game on how many fingers the user will guess to see if he can beat the computer


computer_fingers = rand(6)
puts "How many finger I am holding up"
player_choice = gets.chomp.to_i
puts "I had #{computer_fingers} held out!"
puts "You guessed correctly" if player_choice == computer_fingers

