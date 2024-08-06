# Reconcile emission by using emssion events

### Overview 
This repository is created to demonstrate the process of reconciling emissions using emission events. 

There are three jupyter notebook files are included: 
- **Emission_observations_to_emission_events.ipynb** -> shows how simulated emissions can be used to create emission events.
- **Estimate_duration_uncertainty_for_partially_resolved_events.ipynb** -> demonstrates how Monte Carlo simulation can be used to simulate the duraton uncertainty for partially resolved events.
- **Emissions_from_unresolved_events.ipynb** -> demonstrates how Monte Carlo simulation can be used to estimate emissions from unresolved emission events during the reconciliation time range.

### Data files 
- **Sample_site_simulated_observations_initial_events.csv**: initial 172 emission events created by using simulated 172 emission observations
- **merged_events.csv**: 143 emission events after merged initial 172 emission events based on saptio-temporal correlations
- **my_leak_rate.csv**: component-scale leak rates from datasets organized by Rutherford et al., 2021
- **weather_permian.nc**: weather data in permian basin downloaded from ERA5
- **events_with_duration_unc.csv**: 143 emission events with duration uncetainty for only partially resolved events.
- **Emissions_from_unresolved_events.csv**: simulated emissions from unresolved emission events. 
