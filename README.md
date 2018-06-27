# La-Pyramide-
puts "Combien tu veux d'etages ? "
a = gets.chomp.to_i
n = 1
while n <= a 
  puts ("# " * n).rjust(15)
  n += 1
end
