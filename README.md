# heatsoak_bed.cfg

# Klipper config file

# Heat Soak the Heat bed to allows for Inductive probe drift, this makes temperature more stable for the inductive probe. ANY higher than 65 is not recommentded for an inductive probe, or maybe lower and any other probes
# Please note this Homes the Nozzle
# Please note it takes time for the Heat Bed to heat to the requesed temperature. Therefor the requested time may not be at the full requested temperature all the time requested
# Please note the Heat Bed temperature is left at the requested temperature after this
# Please note Set a new target temperature for the heated bed and waiting. No other commands can take place.
# The heat from the heat bed may damage things like Inductive probes  and any other probes

# Other methods: ( not tested), ALSO View :-
# https://raw.githubusercontent.com/Frix-x/klippain/main/macros/helpers/heatsoak.cfg
# Part of: https://github.com/Frix-x/klippain/tree/main

# Use examples: HEATSOAK_BED TEMPERATURE=45 TIME=7 (7 minutes at 45 degress) , HEATSOAK_BED TEMPERATURE=65 TIME=15 (15 minutes at 65 degress). Klipper only supports the P parameter for milliseconds, not S for seconds.

