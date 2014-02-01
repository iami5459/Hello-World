Hello-World
===========
Class HelloWorldClass
def initalize(name)
@name = name.capitalize
end
def sayHi
puts "Hello #{@name}!"
end
end
hello =HelloWorldClass.new("{Fred}")
hello.sayHi
