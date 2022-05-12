SELECT	AltMeals, HomeMeals

FROM	Customers

WHERE	AltMeals <> 'All' OR HomeMeals <> 'All'


UPDATE	Customers

SET		AltMeals = 'All', HomeMeals = 'All'

WHERE	HomeMeals <> 'All'
