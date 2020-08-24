###  Metrics 
Cost of IC's depend on this:
Area
Testing Cost
Package Type



### Die Cost

IC Cost = (Die Cost + Testing + Packaging) / (Yield)
Die cost = Wafer Cost / (Dies per wafer * Yield)

Dies Per Wafer = (pi*r)^2/(die area) - (2pir)/(sqrt(2x die area))

Yield = wafer yield /(1+Defects per unit area * dies per wafer)^n
n = measure of manufacturing process complexity 

e.g. Calculate yield for IC with 
area = 160mm, 
defect density of 0.05cm 
wafer yield of 91% 
n=5
wafer cost = $6600

Dies per wafer = pi*r^2 / (die area) - (2pi*r)/(sqrt(2*die area)) = 161
yield = 0.91/(1+0.05 * 1.6)^5 = 62%

Good dies per wafer = yield * dies per wafer = 62%*161 = 99.82
IC Cost = wafer cost / good dies per wafer = $6600/99.82= $66.11

###Wafer Size
300mm/200mm = 1.5, area=pi(r)^2
area of 300 mm wafer is larger than 200mm, by a factor of 1.5^2 = 2.25 on same wafer