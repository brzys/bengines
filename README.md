**bengines** is a resource for MTA:SA 1.5 that provides custom engine sounds for vehicles.
Not useful for me anymore so sharing with community. 
Used on old project.
Sounds are copyrighted content not owned by me.

# Features
* ready to use, chooses the best engine for vehicle depending on handling!
* easy to customize & expand for Lua programmers
* 30 soundpacks for vehicles (buses, bikes, sport cars etc.)
* stable code with quite high performance used on server with 600 players
* ALS effect (exhaust flames)
* Turbo (satisfying whistle and blow-off sounds)

# Videos:

* https://streamable.com/n7k40
* https://streamable.com/lp14t
* https://streamable.com/q5e9g


# For programmers:
```lua
--[[ 
Element datas used by resource
[array] vehicle:engine - stores basic info about engine type, sound pack etc. (synced)
[string] vehicle:type - used for engine calculation, useful for servers. Available: Bus, Truck, Sport, Casual, Muscle, Plane, Boat, Motorbike (synced)
[string] vehicle:fuel_type - customized for each engine. Useful for servers. Available: "diesel", "petrol" (synced)
--]]

--[[
Exported functions
--]]

exports.bengines:getVehicleRPM(vehicle) -- returns RPM of given vehicle
exports.bengines:getVehicleGear(vehicle) -- returns current gear of given vehicle
exports.bengines:toggleEngines(bool) -- true / false, restore GTA engine sounds
```
