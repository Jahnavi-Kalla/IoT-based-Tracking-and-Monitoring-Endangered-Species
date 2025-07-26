# IoT-based-Tracking-and-Monitoring-Endangered-Species
An IoT Based System for Tracking and Protecting Endangered Aquatic Species 

Fish Monitoring Prototype

Overview:
This is a Python prototype system for monitoring the health and location of tagged (endangered) fish using both biologging sensors and acoustic multi-hydrophone localization. It demonstrates:
Biologging health alerts: Simulates heart rate, body temperature, and activity; marine biologists are notified of abnormal readings.
Surface GPS tracking: Fish location is logged via GPS when surfaced; collision risk is checked if entering a shipping lane.
Underwater acoustic localization: When GPS is unavailable (underwater), the system estimates fish position using Time of Arrival Difference (ToAD) from multiple hydrophone stations.
Alerts for authorities: Critical health or collision risk events are explicitly flagged for marine biologists or ship captains.
