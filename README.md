# string_enumerator.rb
result = []

"cat".each_char.each_with_index {|item, index| result << [item, index];  }
print result
puts
