This readme file was generated on 2025-02-13 by Tara Jacobsen

General Information
------------------------------------------------------------------------------

Title: NASA's Confirmed Exoplanets:

Author: JamesKYChoi on Kaggle https://www.kaggle.com/datasets/jameskychoi/confirmed-exoplanet-latest-update-dataset 

Additional cleaning by: Tara Jacobsen

Raw Data Source: NASA Exoplanet Archive https://exoplanetarchive.ipac.caltech.edu/index.html

Data Overview
------------------------------------------------------------------------------

As of December 10, 2024, when this dataset was last updated, a total of 5,788 exoplanets have been confirmed. This dataset contains detailed information about these exoplanets organized into over 200 columns, which are derived from a combination of sources.


Methodological Information
------------------------------------------------------------------------------

Data was originally extracted from NASA CSV file to SQL. It was further cleaned with Python. All categorical data was transformed into lowercase characters. All columns were ensured to be lowercase with '_' for spaces. Units and column descriptions can be found below. 

Data is public domain. 


Variable Descriptions
------------------------------------------------------------------------------

| Variable | The variable indicates |
|----------|----------|
| planet_name | Planet name most commonly used in the literature | 
| host_star_name  | Stellar name most commonly used in the literature | 
| planet_letter | Letter assigned to the planetary component of a planetary system | 
| hd_id | Name of the star as given by the Henry Draper Catalog |
| hip_id | Name of the star as given by the Hipparcos Catalog |
| tic_id | Name of the star as given by the TESS Input Catalog|
| gaia_id | Name of the star as given by the Gaia Catalog|
|num_stars_in_system | Number of stars in the planetary system|
| num_planets_in_system|Number of confirmed planets in the planetary system |
| num_moons_in_system|Number of moons in the planetary system |
| is_circumbinary| Flag indicating whether the planet orbits a binary system (1=yes, 0=no)|
| discovery_method| Method by which the planet was first identified|
| discovery_year| Year the planet was discovered|
|discovery_publication_date  |Publication Date of the planet discovery referee publication	(datetime) |
|discovery_locale |Location of observation of planet discovery (ground or space) |
|discovery_facility |Name of facility of planet discovery observations |
| discovery_telescope |Name of telescope of planet discovery observations |
|discovery_instrument | Name of instrument of planet discovery observations|
| detected_by_radial_velocity|Flag indicating if the planet host star exhibits radial velocity variations due to the planet (1=yes, 0=no)	 |
|detected_by_pulsar_timing |Boolean flag indicating if the planet host star exhibits pulsar timing variations due to the planet (1=yes, 0=no)	 |
| detected_by_pulsation_timing_variations|Boolean flag indicating if the planet host star exhibits pulsation timing variations due to the planet (1=yes, 0=no)	 |
| detected_by_transit| Flag indicating if the planet transits its host star (1=yes, 0=no)	|
| detected_by_astrometry| Flag indicating if the planet host star exhibits astrometrical variations due to the planet (1=yes, 0=no)	|
| detected_by_orbital_brightness_modulation|Flag indicating whether the planet exhibits orbital modulations on the phase curve (1=yes, 0=no)	 |
|detected_by_microlensing | Boolean flag indicating if the planetary system acted as a lens during an observed microlensing event (1=yes, 0=no)	|
| detected_by_eclipse_timing_variations| Flag indicating whether a circumbinary planet that orbits an eclipsing binary induces eclipse timing variations (ETVs) in the binary pair (1=yes, 0=no)	|
| detected_by_imaging| Flag indicating if the planet has been observed via imaging techniques (1=yes, 0=no)	|
|detected_by_disk_kinematics | Boolean flag indicating if the presence of the planet was inferred due to its kinematic influence on the protoplanetary disk of its host star (1=yes, 0=no)	|
| is_controversial| |
|orbital_period_days |Time the planet takes to make a complete orbit around the host star or system (days)	 |
| orbital_period_upper_unc_days| Upper uncertainty in the time (in days) the planet takes to complete an orbit around its host star or system |
| orbital_period_lower_unc_days| Lower uncertainty in the time (in days) the planet takes to complete an orbit around its host star or system |
|orbital_period_limit_flag | Flag indicating whether the orbital period is based on a limit (-1=yes, 0=no)|
| orbit_semi_major_axis_au| The longest radius of an elliptic orbit, or, for exoplanets detected via gravitational microlensing or direct imaging, the projected separation in the plane of the sky	|
|orbit_semi_major_axis_upper_unc_au | Upper uncertainty in the orbit semi-major axis (au) |
| orbit_semi_major_axis_lower_unc_au| Lower uncertainty in the orbit semi-major axis (au)|
| orbit_semi_major_axis_limit_flag| Flag indicating whether the orbit semi-major axis is based on a limit (-1=yes, 0=no)|
| angular_separation_mas| Angular separation on the sky between the star and planet in milliarcseconds (mas). |
| angular_separation_limit_flag|Flag indicating whether the angular seperation is based on a limit (-1=yes, 0=no) |
| planet_radius_earth_radius|Length of a line segment from the center of the planet to its surface, measured in units of radius of the Earth	 |
|planet_radius_upper_unc_earth_radius | Upper uncertainty in the planet radius, measured in units of radius of Earth |
|planet_radius_lower_unc_earth_radius | Lower uncertainty in the planet radius, measured in units of radius of Earth|
| planet_radius_earth_limit_flag|Flag indicating whether the planet radius is based on a limit (-1=yes, 0=no) |
|planet_radius_jupiter_radius |Length of a line segment from the center of the planet to its surface, measured in units of radius of Jupiter |
|planet_radius_upper_unc_jupiter_radius | Upper uncertainty in the planet radius, measured in units of radius of Jupiter|
|planet_radius_lower_unc_jupiter_radius |Lower uncertainty in the planet radius, measured in units of radius of Jupiter |
| planet_radius_jupiter_limit_flag|Flag indicating whether the planet radius is based on a limit (-1=yes, 0=no) |
|planet_mass_earth_mass | Amount of matter contained in the planet, measured in units of masses of the Earth	|
| planet_mass_upper_unc_earth_mass| |
| planet_mass_lower_unc_earth_mass| |
|planet_mass_earth_limit_flag | |
| planet_mass_jupiter_mass| Amount of matter contained in the planet, measured in units of masses of Jupiter	|
|planet_mass_upper_unc_jupiter_mass | |
|planet_mass_lower_unc_jupiter_mass | |
| planet_mass_jupiter_limit_flag| |
| planet_mass_provenance|Provenance of the measurement of the best mass. Options are: Mass, M*sin(i)/sin(i), and M*sini	 |
| planet_density_gcm3| Amount of mass per unit of volume of the planet (g/cm**2)|
|planet_density_upper_unc_gcm3 | |
| planet_density_lower_unc_gcm3| |
|planet_density_limit_flag | |
|eccentricity | Amount by which the orbit of the planet deviates from a perfect circle	|
|eccentricity_upper_unc | |
|eccentricity_lower_unc | |
| eccentricity_limit_flag| |
| insolation_flux_earth_flux| Insolation flux is another way to give the equilibrium temperature. It's given in units relative to those measured for the Earth from the Sun.	|
| insolation_flux_upper_unc_earth_flux| |
|insolation_flux_lower_unc_earth_flux | |
|insolation_flux_limit_flag | |
|equilibrium_temperature_k |The equilibrium temperature of the planet as modeled by a black body heated only by its host star, or for directly imaged planets, the effective temperature of the planet required to match the measured luminosity if the planet were a black body (K) |
|equilibrium_temperature_upper_unc_k | |
| equilibrium_temperature_lower_unc_k| |
| equilibrium_temperature_limit_flag| |
|inclination_deg | Angle of the plane of the orbit relative to the plane perpendicular to the line-of-sight from Earth to the object	 (degrees)|
|inclination_upper_unc_deg | |
|inclination_lower_unc_deg | |
| inclination_limit_flag| |
|transit_midpoint_days | The time given by the average of the time the planet begins to cross the stellar limb and the time the planet finishes crossing the stellar limb.	|
|transit_midpoint_upper_unc_days | |
|transit_midpoint_lower_unc_days | |
|transit_midpoint_limit_flag | |
| transit_midpoint_time_system| |
| data_show_transit_timing_variations| Flag indicating if the planet orbit exhibits transit timing variations from another planet in the system (1=yes, 0=no).|
| impact_parameter| The sky-projected distance between the center of the stellar disc and the center of the planet disc at conjunction, normalized by the stellar radius	|
|impact_parameter_upper_unc | |
| impact_parameter_lower_unc| |
|impact_parameter_limit_flag | |
|transit_depth_percent |The size of the relative flux decrement caused by the orbiting body transiting in front of the star	 (%) |
|transit_depth_upper_unc_percent | |
|transit_depth_lower_unc_percent | |
|transit_depth_limit_flag | |
| transit_duration_hours|The length of time from the moment the planet begins to cross the stellar limb to the moment the planet finishes crossing the stellar limb (hours) |
|transit_duration_upper_unc_hours | |
|transit_duration_lower_unc_hours | |
|transit_duration_limit_flag | |
|ratio_semi_major_axis_to_stellar_radius| |
|ratio_semi_major_axis_to_stellar_radius_upper_unc | |
|ratio_semi_major_axis_to_stellar_radius_lower_unc | |
|ratio_semi_major_axis_to_stellar_radius_limit_flag | |
| ratio_planet_to_stellar_radius| |
|ratio_planet_to_stellar_radius_upper_unc | |
|ratio_planet_to_stellar_radius_lower_unc | |
| ratio_planet_to_stellar_radius_limit_flag| |
|epoch_of_periastron_days | |
|epoch_of_periastron_upper_unc_days | |
| epoch_of_periastron_lower_unc_days| |
|epoch_of_periastron_limit_flag | |
|epoch_of_periastron_time_system | |
| argument_of_periastron_deg| |
|argument_of_periastron_upper_unc_deg | |
|argument_of_periastron_lower_unc_deg | |
|argument_of_periastron_limit_flag | |
|radial_velocity_amplitude_ms | |
| radial_velocity_amplitude_upper_unc_ms| |
|radial_velocity_amplitude_lower_unc_ms | |
|radial_velocity_amplitude_limit_flag | |
|projected_obliquity_deg | |
|projected_obliquity_upper_unc_deg | |
| projected_obliquity_lower_unc_deg| |
| projected_obliquity_limit_flag| |
|true_obliquity_deg | |
|true_obliquity_upper_unc_deg | |
|true_obliquity_lower_unc_deg | |
|true_obliquity_limit_flag | |
|spectral_type | |
|stellar_effective_temp_k | |
| stellar_effective_temp_upper_unc_k| |
|stellar_effective_temp_lower_unc_k | |
| stellar_effective_temp_limit_flag| |
|stellar_radius_solar_radius | |
|stellar_radius_upper_unc_solar_radius | |
|stellar_radius_lower_unc_solar_radius | |
|stellar_radius_limit_flag | |
|stellar_mass_solar_mass | |
| stellar_mass_upper_unc_solar_mass| |
|stellar_mass_lower_unc_solar_mass | |
|stellar_mass_limit_flag | |
|stellar_metallicity_dex | |
| stellar_metallicity_upper_unc_dex| |
| stellar_metallicity_lower_unc_dex| |
|stellar_metallicity_limit_flag | |
|stellar_metallicity_ratio | |
| stellar_luminosity_log_solar| |
|stellar_luminosity_upper_unc_log_solar | |
|stellar_luminosity_lower_unc_log_solar | |
| stellar_luminosity_limit_flag| |
| stellar_surface_gravity_log10_cms2| |
|stellar_surface_gravity_upper_unc_log10_cms2 | |
|stellar_surface_gravity_lower_unc_log10_cms2 | |
|stellar_surface_gravity_limit_flag | |
|stellar_age_gyr | |
| stellar_age_upper_unc_gyr| |
|stellar_age_lower_unc_gyr | |
|stellar_age_limit_flag | |
| stellar_density_gcm3 | |
| stellar_density_upper_unc_gcm3 | |
| stellar_density_lower_unc_gcm3 | |
| stellar_density_limit_flag | |
| stellar_rotational_velocity_kms | |
| stellar_rotational_velocity_upper_unc_kms | |
| stellar_rotational_velocity_lower_unc_kms | |
| stellar_rotational_velocity_limit_flag | |
| stellar_rotational_period_days | |
| stellar_rotational_period_upper_unc_days | |
| stellar_rotational_period_lower_unc_days | |
| stellar_rotational_period_limit_flag | |
| systemic_radial_velocity_kms | |
| systemic_radial_velocity_upper_unc_kms | |
| systemic_radial_velocity_lower_unc_kms | |
| systemic_radial_velocity_limit_flag | |
| ra_str | |
| ra_deg | |
| dec_str | |
| dec_deg | |
| galactic_latitude_deg | |
| galactic_longitude_deg | |
| ecliptic_latitude_deg | |
| ecliptic_longitude_deg | |
| total_proper_motion_mas_yr | |
| total_proper_motion_upper_unc_mas_yr | |
| total_proper_motion_lower_unc_mas_yr | |
| proper_motion_ra_mas_yr | |
| proper_motion_ra_upper_unc_mas_yr | |
| proper_motion_ra_lower_unc_mas_yr | |
| proper_motion_dec_mas_yr | |
| proper_motion_dec_upper_unc_mas_yr | |
| proper_motion_dec_lower_unc_mas_yr | |
| distance_pc | |
| distance_upper_unc_pc | |
| distance_lower_unc_pc | |
| parallax_mas | |
| parallax_upper_unc_mas | |
| parallax_lower_unc_mas | |
| b_magnitude_johnson | |
| b_magnitude_johnson_upper_unc | |
| b_magnitude_johnson_lower_unc | |
| v_magnitude_johnson | |
| v_magnitude_johnson_upper_unc | |
| v_magnitude_johnson_lower_unc | |
| j_magnitude_2mass | |
| j_magnitude_2mass_upper_unc | |
| j_magnitude_2mass_lower_unc | |
| h_magnitude_2mass | |
| h_magnitude_2mass_upper_unc | |
| h_magnitude_2mass_lower_unc | |
