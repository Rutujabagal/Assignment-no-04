# Experimental Determinations

Gca = float(input(“Enter the value of specific gravity of CA: “))

Gfa = float(input(“Enter the value of specific gravity of FA: “))

Gc = float(input(“Enter the value of specific gravity of Cement: “))

Water_density = float(input(“Enter the value of Water Density: “))

Agg_size = float(input(“Enter the nominal Size of Aggregate: “))

Nature_of_agg = input(“Nature of Aggregates: “)

Slump = float(input(“Enter the value of workability (slump) of concrete: “))

Admixture = input(“Type of Admixture: “)

Exposure_condition = input(“Exposure Condition: “)

Concreting_type = input(“Type of Concreting: “)

Zone = int(input(“Zone (1 to 4): “))

# Target Mean Strength (assuming some relationship, may need to adjust formula)

Sigma = 5 # Just a placeholder value

Ft = fck + 1.65 * sigma

Print(“Target Mean Strength: “, ft, “MPa”)

# Maximum free Water Cement Ratio (based on IS 456:2000)

If concreting_type == “Plain”:

 Wc_ratios = {“Mild”: 0.6, “Moderate”: 0.5, “Severe”: 0.5, “Very Severe”: 0.45, “Extre
