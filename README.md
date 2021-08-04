# Ajoneuvodata
Open vehicle data

These cars will be registered in Finland in 2019-2021

What are the most popular models and brands in first registrations from 2019 to February 2021? What are the most popular colors with the most popular brands? What were the most popular drives and transmissions? Which brand has the most electric hybrids in its collection? What are the average emissions of electric hybrids? And how much have emissions decreased on average since the mid-1990s?

I was looking for answers to these questions when I went through the open vehicle 5.13 data on Traficom’s website. The open vehicle data contains the registration, approval and technical information of all vehicles in traffic from the traffic register maintained by Traficom.

The material can be found at: https://www.traficom.fi/fi/ajanohtaista/avoin-data

The material had a total of 5,121,148 lines and was published on 3 February 2021. I extracted the data from the data only for passenger cars (vehicle categories M1 and M1G) and limited it to the first registered from the beginning of 2019. I processed the material with Python. At the end of the article is a link to the Python code.

What are the most popular brands? Toyota, Volvo and Mercedez-Benz are at the forefront.

What are the most popular models again? The top three are made up of Nissan, Toyota and Skoda models.

What are the most popular colors for first registration? The most popular colors with the most popular brands varied. Gray was the most popular color for Skoda and Suzuki. Black is preferred by Audi, BMW, Mercedes-Benz and Volvo drivers. Red riders liked Red the most. White was the most popular on several brands.

What are the most popular driving forces? Rumors of an internal combustion engine death seem to be strongly exaggerated. Gasoline is strongly in the pole position and diesel is second. Two out of 100 initial registrations were done using electrical technology.

What are the most popular gearboxes? Two of the three chose the vending machine.

It was also interesting to know which brand's collection has the most electric hybrids? At the forefront are Toyota, Mitsubishi and Volvo. The average CO2 emissions of newly registered electric hybrids are about 98 grams.

The development of internal combustion engine technology in cars is strongly reflected in the development of CO2 emissions. Emissions have fallen sharply since the mid-1990s. As late as the mid-1990s, emissions were around 220, up from now averaging around 130.
