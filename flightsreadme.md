# Flights Data Exploration

## Dataset

The data consists of information regarding 100000 flights including departure time, delay time, quarter and other columns.

The dataset can be found in the
repository https://github.com/sophfel/flight_project/blob/main/flights_clean.csv,
with feature documentation available https://www.transtats.bts.gov/Fields.asp?Table_ID=236


## Summary of Findings

Delay and original time was positively correlated which was found before.I found that the 3rd quarter had more delays on a Saturday and less on a Tuesday, this strengthens what I found in the bivariate. The 1st and 4th quarter has lowest delays on a Sunday and highest on a Thursday.

Looking at airlines, delay and quarter. The 3rd quarter had the most general, weather, carrier and NAS delays, the lowest being in the 4th quarter. Results strengthened what I found before. YV had the highest delays overall of all 4 quarters, this was also seen when looking at weather delay in the 3rd quarter. OO had the most weather delays in the other quarters. In all quarters, carrier delay and NAS delay seemed to be equal. The late aircraft delay was higher and equal in all quarters slightly less in the 4th. Security delay is negligible. This solidifys that more delays happened in the 3rd quarter.

YV only flew from Malone and had the most delays, whilst HA only flew from JFK. The airline with the most delays from JFK was OO. I found that NK had the highest NAS delays and HA had the lowest. The 4th quarter had the least delays ad 3rd had the highest.

Overall, Saturday had the most delays with the highest quarter being 3rd and the lowest quarter was 2nd. The least delays seemed to happen midweek. For both airports, Saturday seemed to have the most delays. For Malone, Tuesday was the lowest and JFK, Sunday was the lowest.

I found before that NAS was highest on a Thursday and this was found again in the 4th quarter but not in the 3rd. Security delay seemed to happen in the 1st quarter more on a Tuesday and on a Thursday in the other quarters. There was not much difference otherwise. I did not look at the other types of delay due to not finding a difference before.

The least amount of flights seem to take off on a Saturday and in the 4th quarter. The most flights took off on a Wed in the 2nd quarter.

It was found that weather delay happened more in the morning and evening throughout the year. The least weather delays happened in the 4th quarter and the most in the 3rd. All 4 quarters had a positive correlation between weather delay and dep time. With carrier delay, the 3rd quarter was the highest and the 4th was the lowest. Security, same trend throughout the quarters. Late aircraft, 3rd and 4th quarter seemed to have the most delays with similar trends.

Overall, JFK had more weather, carrier and NAS delays than Malone, the 3rd quarter was the highest for all 3 types and the 2nd was the lowest for weather, but 1st was lower for NAS and carrier delays. For Malone, the 3rd quarter had the most delays in all 3 types and the 4th had the lowest weather delays, but the 1st quarter had the least carrier and NAS delays.

Malone had more security and late aircraft delays, both having more in the 4th quarter and least in the 1st. JFk had most late aircrafts in the 3rd quarter but most security delays in the 2nd. There were least late aircrafts in the 4th but lease secuirty delays in the 1st.

Were there any interesting or surprising interactions between features?
Less flights took off from JFK but there were still more weather, carrier and late aircrafts from there.

It surprised me that the least flights took off on a Saturday and in the 4th quarter and the most took off in the 2nd quarter on a Wed. The 3rd quarter seems to have the most delays overall as found before but not the highest amount of flights.


## Key Insights for Presentation

For the presentation, I start by looking at general delay and departure time divided into the quarters. I then looked at days of the week. 

I then looked at the delay according to airlines and then airport. I finish by looking at the different types of delay in the quarters of the year to see the difference.
