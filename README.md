# Flight-Delay-Project
Project 1 Flight Delay Tracker
Aviation Delay Statistics 2023

Final data analysis
Due to the API key limitation, we could retrieve a flight data which covers one week starting from September 4 until September 10. This week was picked as the most recent and busy time after Labor day. In total, 3765 departure flights took off from SFO during this period. For clarity, we consider departure fligths only. Note that the codesharing flights were removed from our dataset (same flights operating under different flight numbers). We consider a flight to be delayed if the time delay is more than 30 minutes. We introduce a delay ratio parameter. The delay ratio (in %) is calculated as the total number of delayed flights normalized per the total flights per airline.  
The major airline operating in SFO is United Airlines accounting for 1624 departure flights, while the total number of airlines is 84 (private jets etc. included). Among the top five airlines (United, Alaska, Delta, Delta, JetBlue, and American), JetBlue showed worse performance showing a delay ratio of 40.2%. Alaskan Airlines showed the lowest delay ratio of 16.2%. Delta and American also demonstrate low delay ratios (16.6 and 17.0%, respectively), but longer average delay. However, a closer look into the average delay (mean per airline) revealed that the delay statistics did not obey the normal distribution. Thus, the average delay should be considered with precautions (one or two long-delayed flights may bias the results). We also mapped the arrival locations on domestic and world map. The top destination is LAX (Los Angeles) in the United States, while the global map showed no flights to Africa at all. 
Please, find attached a link below to the slide deck for more details,
https://docs.google.com/presentation/d/1tjoGSTzrcJ8qsPxetJmr8cyY7kVrKHhZOSymK63_4CA/edit#slide=id.gc6f73a04f_0_0
Thanks
Corgi Tattoo Crew 
