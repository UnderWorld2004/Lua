--Lua
--Basic Lua Code
--Code that calculates your note if you failed.
print("Cual es tu calificacion: ")
local system_grade = tonumber(io.read())
if system_grade >= 90 then
  print("Tu eres un erudito")
 elseif system_grade >= 80 then 
   print("Tu eres inteligente")
 elseif system_grade >= 70 then
   print("Eres promedio")
 elseif system_grade >=60 then
 print("Eres raro")
elseif system_grade <=50 then
 print("Estas reprobado")
end

