# simulink-multiband-noise-block
Simulink&reg; block that models noise acting on four different timescales

This block models multiband noise by adding four different band limited white noise signals, each one with its own power and time scale, with three of them being also filtered by a lowpass first order filter.

NOTE: I made this - I think - in an effort to model the noise typically observed by a gps receiver. But it is a toy model and a _very_ uneducaded guess. I do suggest you look at more authoritative sources as for example this one: https://www.geologie.ens.fr/~ecalais/teaching/gps-geodesy/gps_noise_models.pdf
