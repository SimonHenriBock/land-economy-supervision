# Analysis

-	Market potential: Computed Harris MP for each NUTS2 region, as in supo 2: MPᵢ = Σⱼ Yⱼ / dᵢⱼ, with internal distance dᵢᵢ = ⅔√(areaᵢ/π). 
-	Energy endowment: Added up renewable capacity (MW) per region, scaled by area or population.
-	Assigned projects to regions with a spatial join on coordinates.
-	Descriptive test: Compared where project regions sit in the distribution of MP and of renewables (percentiles), by sector. 
-	Simple regression: Modelled the number of projects (or a 0/1 for having any) on log MP, log renewables, manufacturing share and a port dummy, with country fixed effects, ran separately for batteries and steel/hydrogen.
-	Price-zone test: compared project locations for Sweden and Norway with zonal prices from ENTSO-E. Germany is the counterfactual with a single price.
-	Survival check: Are cancelled projects more often in energy-driven peripheral locations or in core locations? This tells me the robustness of results
	I set out the research approach/strategy and then prompted Claude to execute the calculations and statistical analyses
