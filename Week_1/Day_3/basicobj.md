# Some basic obj notes
make sure to not assign undefined to a key, because undefined carries a lot of semantic weight. 

for (let var of array) -- Arrays

for (let key in obj) -- Objs

### Note, limitations of for.. in..
if (planetMoons.hasOwnProperty(planet)) {

must use this to addess inherited methods and properties. 