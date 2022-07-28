# Lua Astronomy
*Lua is a minimalist language. Compared with Python, its performance is very good, and it is easy to integrate with professional programming languages such as C++.*
*Astronomy is a computationally intensive science, astronomical instruments are expensive and shared, and most people work with data processing and computation.*
*Combining the two may collide with sparks*

## Dimension
Dimensions translate mathematics into science. It is easiest to calculate physical quantities in the same way as dimensional transformation.The international unit is ignored here, and other dimensions are defined as follows:
```
nm = 1e-9	-- m
cm = 0.01	-- cm
mm = 0.001	-- mm

c = 299792458 --m/s

au = 149597870700 -- m 

ly = 9.4607e12	-- m

arc_second	= math.pi / 180.0 / 3600.0 

min_arc_second = 0.01

Proxima_Centauri_dis = 4.2 * ly

-- distance of per arc_second per year 
pc = (au) / arc_second -- example : pc / Proxima_Centauri_dis

rad_deg = math.pi / 180.0

arc_second_degree = arc_second * 180 / math.pi 
```
