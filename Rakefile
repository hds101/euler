require 'bundler/setup'
Bundler.require :default

task :problem_1 do
  puts 'If we list all the natural numbers below 10 that are multiples of ' \
       '3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.'
  puts 'Find the sum of all the multiples of 3 or 5 below 1000.'

  sum = 1000.times.inject(0) do |acc, e|
    acc + (((e % 3).zero? || (e % 5).zero?) ? e : 0)
  end
  puts "The sum is #{sum}"
end
