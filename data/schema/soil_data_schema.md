# Soil Health Model — Data Schema

## Sample Identification

- sample_id
- farm_id
- field_id
- plot_id
- sampling_date
- sampling_depth
- location_class

## Laboratory Data

- pH
- nitrogen
- phosphorus
- potassium
- organic_carbon
- electrical_conductivity
- moisture
- soil_texture

## Sensor Data

- soil_moisture
- soil_temperature
- soil_conductivity
- other_available_sensor_measurements

## Weather Data

- temperature
- rainfall
- humidity
- weather_timestamp

## Crop and Field Context

- crop
- variety
- crop_history
- irrigation_history
- fertilizer_history
- field_information

## Textual Agricultural Information

- farmer_observation
- soil_observation
- crop_observation
- other_relevant_text

## Soil Images

- image_path
- image_id
- image_quality
- calibration_information

## Targets

- pH
- nitrogen
- phosphorus
- potassium
- organic_carbon
- electrical_conductivity
- moisture
- soil_texture
- deficiency
- soil_health_score
- salinity_or_degradation_risk
- crop_suitability