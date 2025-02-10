This readme file was generated on 2025-02-13 by Tara Jacobsen

GENERAL INFORMATION
------------------------------------------------------------------------------

Title: NASA's Confirmed Exoplanets:

Author: JamesKYChoi on Kaggle https://www.kaggle.com/datasets/jameskychoi/confirmed-exoplanet-latest-update-dataset 

Cleaned by: Tara Jacobsen

Raw Data Source: NASA Exoplanet Archive https://exoplanetarchive.ipac.caltech.edu/index.html

DATA OVERVIEW
------------------------------------------------------------------------------

As of December 10, 2024, when this dataset was last updated, a total of 5,788 exoplanets have been confirmed. This dataset contains detailed information about these exoplanets organized into over 200 columns, which are derived from a combination of sources.


METHODOLOGICAL INFORMATION
------------------------------------------------------------------------------

Data was originally extracted from NASA CSV file to SQL. It was further cleaned with Python. All categorical data was transformed into lowercase characters. All columns were ensured to be lowercase with '_' for spaces. Units and column descriptions can be found below. 

Data is public domain. 


VARIABLE DESCRIPTIONS
------------------------------------------------------------------------------

Variable:                                             The variable indicates:
------------------------------------------------------------------------------

planet_name                                           Planet name most commonly used in the literature	
host_star_name                                        Stellar name most commonly used in the literature   
planet_letter                                         Letter assigned to the planetary component of a planetary system	
hd_id                                                 Name of the star as given by the Henry Draper Catalog	
hip_id                                                Name of the star as given by the Hipparcos Catalog	
tic_id                                                Name of the star as given by the TESS Input Catalog	
gaia_id                                               Name of the star as given by the Gaia Catalog	
num_stars_in_system                                   Number of stars in the planetary system	
num_planets_in_system                                 Number of confirmed planets in the planetary system	
num_moons_in_system                                   Number of moons in the planetary system	
is_circumbinary                                       Flag indicating whether the planet orbits a binary system (1=yes, 0=no)	
discovery_method                                      Method by which the planet was first identified	
discovery_year                                        Year the planet was discovered	
discovery_publication_date                            Publication Date of the planet discovery referee publication	(datetime)
discovery_locale                                      Location of observation of planet discovery (ground or space)	
discovery_facility                                    Name of facility of planet discovery observations	
discovery_telescope                                   Name of telescope of planet discovery observations	
discovery_instrument                                  Name of instrument of planet discovery observations	
detected_by_radial_velocity
detected_by_pulsar_timing
detected_by_pulsation_timing_variations
detected_by_transit
detected_by_astrometry
detected_by_orbital_brightness_modulation
detected_by_microlensing
detected_by_eclipse_timing_variations
detected_by_imaging
detected_by_disk_kinematics
is_controversial
orbital_period_days
orbital_period_upper_unc_days
orbital_period_lower_unc_days
orbital_period_limit_flag
orbit_semi_major_axis_au
orbit_semi_major_axis_upper_unc_au
orbit_semi_major_axis_lower_unc_au
orbit_semi_major_axis_limit_flag
angular_separation_mas
angular_separation_limit_flag
planet_radius_earth_radius
planet_radius_upper_unc_earth_radius
planet_radius_lower_unc_earth_radius
planet_radius_earth_limit_flag
planet_radius_jupiter_radius
planet_radius_upper_unc_jupiter_radius
planet_radius_lower_unc_jupiter_radius
planet_radius_jupiter_limit_flag
planet_mass_earth_mass
planet_mass_upper_unc_earth_mass
planet_mass_lower_unc_earth_mass
planet_mass_earth_limit_flag
planet_mass_jupiter_mass
planet_mass_upper_unc_jupiter_mass
planet_mass_lower_unc_jupiter_mass
planet_mass_jupiter_limit_flag
planet_mass_provenance
planet_density_gcm3
planet_density_upper_unc_gcm3
planet_density_lower_unc_gcm3
planet_density_limit_flag
eccentricity
eccentricity_upper_unc
eccentricity_lower_unc
eccentricity_limit_flag
insolation_flux_earth_flux
insolation_flux_upper_unc_earth_flux
insolation_flux_lower_unc_earth_flux
insolation_flux_limit_flag
equilibrium_temperature_k
equilibrium_temperature_upper_unc_k
equilibrium_temperature_lower_unc_k
equilibrium_temperature_limit_flag
inclination_deg	inclination_upper_unc_deg
inclination_lower_unc_deg
inclination_limit_flag
transit_midpoint_days
transit_midpoint_upper_unc_days
transit_midpoint_lower_unc_days
transit_midpoint_limit_flag
transit_midpoint_time_system
data_show_transit_timing_variations
impact_parameter
impact_parameter_upper_unc
impact_parameter_lower_unc
impact_parameter_limit_flag
transit_depth_percent
transit_depth_upper_unc_percent
transit_depth_lower_unc_percent
transit_depth_limit_flag
transit_duration_hours
transit_duration_upper_unc_hours
transit_duration_lower_unc_hours
transit_duration_limit_flag
ratio_semi_major_axis_to_stellar_radius
ratio_semi_major_axis_to_stellar_radius_upper_unc
ratio_semi_major_axis_to_stellar_radius_lower_unc
ratio_semi_major_axis_to_stellar_radius_limit_flag
ratio_planet_to_stellar_radius
ratio_planet_to_stellar_radius_upper_unc
ratio_planet_to_stellar_radius_lower_unc
ratio_planet_to_stellar_radius_limit_flag
epoch_of_periastron_days
epoch_of_periastron_upper_unc_days
epoch_of_periastron_lower_unc_days
epoch_of_periastron_limit_flag
epoch_of_periastron_time_system
argument_of_periastron_deg
argument_of_periastron_upper_unc_deg
argument_of_periastron_lower_unc_deg
argument_of_periastron_limit_flag
radial_velocity_amplitude_ms
radial_velocity_amplitude_upper_unc_ms
radial_velocity_amplitude_lower_unc_ms
radial_velocity_amplitude_limit_flag
projected_obliquity_deg
projected_obliquity_upper_unc_deg
projected_obliquity_lower_unc_deg
projected_obliquity_limit_flag
true_obliquity_deg
true_obliquity_upper_unc_deg
true_obliquity_lower_unc_deg
true_obliquity_limit_flag
spectral_type
stellar_effective_temp_k
stellar_effective_temp_upper_unc_k
stellar_effective_temp_lower_unc_k
stellar_effective_temp_limit_flag
stellar_radius_solar_radius
stellar_radius_upper_unc_solar_radius
stellar_radius_lower_unc_solar_radius
stellar_radius_limit_flag
stellar_mass_solar_mass
stellar_mass_upper_unc_solar_mass
stellar_mass_lower_unc_solar_mass
stellar_mass_limit_flag
stellar_metallicity_dex
stellar_metallicity_upper_unc_dex
stellar_metallicity_lower_unc_dex
stellar_metallicity_limit_flag
stellar_metallicity_ratio
stellar_luminosity_log_solar
stellar_luminosity_upper_unc_log_solar
stellar_luminosity_lower_unc_log_solar
stellar_luminosity_limit_flag
stellar_surface_gravity_log10_cms2
stellar_surface_gravity_upper_unc_log10_cms2
stellar_surface_gravity_lower_unc_log10_cms2
stellar_surface_gravity_limit_flag
stellar_age_gyr
stellar_age_upper_unc_gyr
stellar_age_lower_unc_gyr
stellar_age_limit_flag
stellar_density_gcm3
stellar_density_upper_unc_gcm3
stellar_density_lower_unc_gcm3
stellar_density_limit_flag
stellar_rotational_velocity_kms
stellar_rotational_velocity_upper_unc_kms
stellar_rotational_velocity_lower_unc_kms
stellar_rotational_velocity_limit_flag
stellar_rotational_period_days
stellar_rotational_period_upper_unc_days
stellar_rotational_period_lower_unc_days
stellar_rotational_period_limit_flag
systemic_radial_velocity_kms
systemic_radial_velocity_upper_unc_kms
systemic_radial_velocity_lower_unc_kms
systemic_radial_velocity_limit_flag
ra_str
ra_deg
dec_str
dec_deg
galactic_latitude_deg
galactic_longitude_deg
ecliptic_latitude_deg
ecliptic_longitude_deg
total_proper_motion_mas_yr
total_proper_motion_upper_unc_mas_yr
total_proper_motion_lower_unc_mas_yr
proper_motion_ra_mas_yr
proper_motion_ra_upper_unc_mas_yr
proper_motion_ra_lower_unc_mas_yr
proper_motion_dec_mas_yr
proper_motion_dec_upper_unc_mas_yr
proper_motion_dec_lower_unc_mas_yr
distance_pc
distance_upper_unc_pc
distance_lower_unc_pc
parallax_mas
parallax_upper_unc_mas
parallax_lower_unc_mas
b_magnitude_johnson
b_magnitude_johnson_upper_unc
b_magnitude_johnson_lower_unc
v_magnitude_johnson
v_magnitude_johnson_upper_unc
v_magnitude_johnson_lower_unc
j_magnitude_2mass
j_magnitude_2mass_upper_unc
j_magnitude_2mass_lower_unc
h_magnitude_2mass
h_magnitude_2mass_upper_unc
h_magnitude_2mass_lower_unc