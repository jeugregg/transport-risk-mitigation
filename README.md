# transport-risk-mitigation
ML Model for Transport Risk Mitigation  

Ocean Protocol Data Challenge : https://desights.ai/shared/challenge/10  
Ocean Protocol, a web3 Data/AI ecosystem : https://oceanprotocol.com/

The objective is to develop ML models using the provided dataset, to predict potentially dangerous temperature and humidity conditions while transporting high-value goods, including livestock and perishable food items. By analyzing telematics, weather data, and sensor readings, the model will uncover the influence of external weather, geolocation, and internal microclimate on transport conditions.  

The primary goal is to forecast instances where temperatures may exceed 25°C and/or humidity levels may surpass 80%.  

Data source : https://drive.google.com/drive/folders/1_-Eh_BXhjSkKtJ-s1rrMXxsE9Z6EfteN  


- Analytics
  - Find correlations between geolocation, external weather, timestamp, and internal microclimate data. How are these pillars interconnected?
  - How does this interconnectedness influence the risk of dangerous temperatures or humidity?
  - How do specific weather events (like high winds) or variables such as the proximity of farms to roads contribute to temperature risk?
  - How can the risk of temperature or humidity-related issues be minimized for long-distance transportation events?
  - What combination of internal and external weather factors conclude an ideal temperature that is less than 25 degree celsius and less than 80% humidity?

- Prediction Model
  - Build a model taking as input data from the "Sensor-Fusion Data" dataset to determine the current indoor temperature and humidity (the "value" column in the "Microclimate Sensor -Readings" dataset). Once the model has been created, use it to simulate a trip of your choice. You will be judged on your choice of features and model.

- Prediction Model for indoor
  - Build a model that predicts indoor temperature and humidity a few minutes/seconds into the future. This requires data transformation. If you can create a model, show us how!

- Report: 
  - report describing the above findings : file into /doc/
