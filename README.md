# Demography

Demography is the scientific study of human populations, including their size, composition, distribution, and changes over time. It examines patterns of birth, death, and migration, as well as the social, economic, and environmental factors that influence these patterns. Demography also involves the use of statistical methods to analyze and interpret data on population characteristics, such as age, gender, race, ethnicity, education, and income. The information generated by demography is useful for understanding and addressing a wide range of social and economic issues, such as public health, education, labor markets, and housing.

## population density

```py
def population_density(population, area):
    density = population / area
    return density
```
## Birth rate per capita

```py
def birth_rate(births, population):
    rate = births / population
    return rate
```
## Death rate per capita

```py
def death_rate(deaths, population):
    rate = deaths / population
    return rate
```

## Life expectancy

```py
def life_expectancy(age, gender):
    if gender == 'male':
        life_expectancy = 76.1 - age
    elif gender == 'female':
        life_expectancy = 80.8 - age
    else:
        life_expectancy = None
    return life_expectancy
```

## Age-specific fertility rate

```py
def age_specific_fertility_rate(live_births, women_population):
    asfr = live_births / women_population
    return asfr
```

## infant mortality rate

```py
def infant_mortality_rate(infant_deaths, live_births):
    imr = infant_deaths / live_births
    return imr
```

## Total fertility rate

```py
def total_fertility_rate(births, women_population):
    tfr = births / women_population * 1000
    return tfr
```

## net migration rate

```py
def net_migration_rate(incoming_population, outgoing_population, total_population):
    nmr = (incoming_population - outgoing_population) / total_population * 1000
    return nmr
```



