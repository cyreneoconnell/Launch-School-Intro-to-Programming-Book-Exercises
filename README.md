# Launch-School-Intro-to-Programming-Book-Exercises
Code exercises I completed while working through the Intro to Programming Book on launchschool
Basic Exercises: Chapter 1
irb(main):002:0> "Cyrene" + " O'Connell"
=> "Cyrene O'Connell"
irb(main):003:0> thousands = 5628 / 1000
=> 5
irb(main):004:0> hundreds = 5628 % 1000 / 100
=> 6
irb(main):005:0> tens = 5628 % 100 / 10
=> 2
irb(main):006:0> ones = 5628 % 10
=> 8
irb(main):008:1* movies = {Star_Wars: 2015, Anchorman: 2004, Neighbors: 2014, Snatch: 2002, The Departed: 2007}
irb(main):009:1> puts movies [:Star_Wars]
irb(main):010:1> puts movies [:Anchorman]
irb(main):011:1> puts movies [:Neighbors]
irb(main):012:1> puts movies [:Snatch]
irb(main):013:1> puts movies [:The_Departed]
irb(main):014:1> dates = [2015, 2004, 2014, 2002, 2007]
irb(main):015:1> puts dates [0]
irb(main):016:1> puts dates [1]
irb(main):017:1> puts dates [2]
irb(main):018:1> puts dates [3]
irb(main):019:1> puts dates [4]
irb(main):021:1> puts 5 * 4 * 3 * 2 * 1
irb(main):022:1> puts 6 * 5 * 4 * 3 * 2 * 1
irb(main):023:1> puts 7 * 6 * 5 * 4 * 3 * 2 * 1
irb(main):024:1> puts 8 * 7 * 6 * 5 * 4 * 3 * 2 * 1
irb(main):026:1> puts 45.85 * 45.85
irb(main):027:1> puts 6.20 * 6.20
irb(main):028:1> puts 963.4 * 963.4
Chapter 2:Variables
irb(main):001:0> # name.rb
irb(main):002:0* puts "What is your name?"
What is your name?
=> nil
irb(main):003:0> name = gets.chomp
Cyrene
=> "Cyrene"
irb(main):004:0> puts "Hello" + name
HelloCyrene
=> nil
irb(main):005:0> # age.rb
irb(main):006:0* puts "How old are you?"
How old are you?
=> nil
irb(main):007:0> age = 30
=> 30
irb(main):008:0> # age.rb
irb(main):009:0* puts "How old are you?"
How old are you?
=> nil
irb(main):010:0> age = gets.chomp.to_i
30
=> 30
irb(main):011:0> puts "In 10 years you will be:"
In 10 years you will be:
=> nil
irb(main):012:0> puts 30 + 10
40
=> nil
irb(main):013:0> puts "In 20 years you will be:"
In 20 years you will be:
=> nil
irb(main):014:0> puts 30 + 20
50
=> nil
irb(main):015:0> puts "In 30 years you will be:"
In 30 years you will be:
=> nil
irb(main):016:0> puts 30 + 30
60
=> nil
irb(main):017:0> puts "In 40 years you will be:"
In 40 years you will be:
=> nil
irb(main):018:0> puts 30 + 40
70
=> nil
irb(main):008:0> 10.times do
irb(main):009:1* puts "Cyrene"
irb(main):010:1> end
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
Cyrene
=> 10
irb(main):011:0> puts "What is your first name?"
What is your first name?
=> nil
irb(main):012:0> first_name = gets.chomp
Cyrene
=> "Cyrene"
irb(main):013:0> puts "Thank you. What is your last name?"
Thank you. What is your last name?
=> nil
irb(main):014:0> last_name = gets.chomp
O'Connell
=> "O'Connell"
irb(main):015:0> puts "Awesome. So your full name is " + first_name + last_name
Awesome. So your full name is Cyrene O'Connell

