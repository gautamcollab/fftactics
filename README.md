
## Lesson Plan 

Create database tables and mocking up a schema w/o ActiveRecord
This shows you how we'd do with raw SQL 


##Database

Party
-Units (players) 

Unit (belongs to a party) 
-HP, MP, Job, atk, def, equipment 

Create a table of weapons
a weapon will have its own ID 
find a units weapon by the weapons ID
Example: weapon = Weapon.find(unit.weapon_id)