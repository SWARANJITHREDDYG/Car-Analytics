# DATA DICTIONARY — Car Analytics Project

### 1. car_id  
Unique identifier for each car.

### 2. brand  
Manufacturer of the car (Hyundai, Toyota, BMW, etc.)

### 3. model  
Model/variant name of the car.

### 4. manufacturing_year  
Year in which the car was manufactured.

### 5. fuel_type  
Type of fuel used by the car (Petrol, Diesel).

### 6. transmission  
Type of transmission (Manual / Automatic).

### 7. engine_cc  
Engine displacement in cubic centimeters.

### 8. max_power_bhp  
Maximum power produced by the engine (in BHP).

### 9. mileage_kmpl  
Mileage of the car (km per litre).

### 10. km_driven  
Total distance the car has been driven (in kilometers).

### 11. location  
City where the car is listed.

### 12. car_price  
Selling price of the car (in INR).

---

# ENGINEERED FEATURES (Added in Task 1)

### 13. car_age  
Calculated as:  
`car_age = 2025 - manufacturing_year`  
Represents how old the car is.

### 14. price_per_cc  
Price divided by engine CC.  
Indicates cost per engine capacity unit.

### 15. price_per_km  
Price divided by kilometers driven.  
Indicates how expensive the car is relative to usage.
