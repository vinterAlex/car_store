# car_store
Car store using postman and C#
# using postman : 

-- to get the vehicles
"localpath:port/api/vehicle" -- will return all vehicles from the db
"localpath:port/api/vehicle/{vehicleID}"

-- to get all the make's of the vehicles
"localpath:port/api/vehiclemake/" -- will return all make's of the vehicles and the id's for you to use them below

-- to get all the vehicles with that makeID
"localpath:port/api/vehiclemake/30" -- will return all vehicles with that make ID
