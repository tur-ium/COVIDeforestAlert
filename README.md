## Welcome to __COVIDeforestAlert__
### A [NASA Space Apps Challenge entry](spaceappschallenge.org) from [Team __COVID Forest Watch__](https://covid19.spaceappschallenge.org/challenges/covid-challenges/sdgs-and-covid-19/teams/covid-forest-watch/project)

Challenge category: SDGs and COVID-19

## See the [Live Code Dashboard](https://drive.google.com/file/d/1JsWFrlaSRTpoUcufPCYXxbX_h1pY4aAs/view?usp=sharing). 

### How to use COVIDeforestationAlert
1. Go to the [live version](https://github.com/tur-ium/COVIDeforestAlert/). You may be asked to log in with a Google account*.
2. Choose a country. Choices: "BRA" (Brazil), "COL" (Colombia), or any 3 letter country code from here https://www.worldatlas.com/aatlas/ctycodes.htm  The country must be close to the equator (within 30 degree north or south), otherwise deforestation data won't be available
3. Go to ``Runtime`` -> ``Run All`` in the top menu
4. Scroll down to the bottom of the page to see a graph of deforestation events against number of COVID cases
We use Python and Jupyter notebook in order to produce the interface

* If this is not an option, you can run the version from [GitHub](https://github.com/tur-ium/COVIDeforestAlert/) on your own computer.

### The Problem

Conservation International recently reported on their website that an increase in deforestation rates has been seen in countries such as Colombia and Brazil (Conservation International, 2020). Our first aim is to use satellite imagery to test the claims of Conservation International, and explore possible causations of forest change in Brazil and Colombia since the COVID-19 crisis began to affect those regions. 

Possible explanations for why deforestation might increase while governments are forced to limit activity, if true, include the following:
    1. Good fuels used for cooking are not available or too expensive, especially butane and kerosene. Therefore people turn to using wood which is cheaper, but has a lower energy content and drives an increase in demand for wood, and hence logging of natural forests.
    2. Loss of income due to the necessary measures to reduce the spread of the disease, means people look for other forms of employment to sustain themselves. In particular, jobs in catering, tourism, and informal workers might be more likely to have to look for other forms of work, such as in the timber industry or mining.
    3. Opportunism. People look to grab forest land while governments in NGOs are distracted by coping with the virus, or unable to monitor activity on the ground, in order to later mine or farm the land.

None of these explanations are specifc to Brazil or Colombia, and so it is possible these trends if true, may be occurring in other low- and middle- income countries. This leads to the second aim of COVIDeforestAlert: explore whether forest changes have occurred in other regions beyond Brazil and Colombia that could be caused by COVID-19.

#### Setting the scene: Could this be life in a remote town in Africa during COVID? 
[This is a fictious story]

You are in your hut. The town is in quarantine because of the pandemic.  Someone is coughing in another house. The police are on the streets with batons, and though you are safe inside, videos of what batons have been used for are all over social media and messenger groups. The little hairdressing salon you run is shut; your son, who is in Europe,  has lost his job and you won't ask him to send  money, as you have done in the past, when times were tight. Even if he could send money, it would be a two hour wait in the queue at the money transfer kiosk, packed side by side, with people coughing.

The shops are running low in supplies. When you last went out, there were few gas cylinders,  and the ones that left were triple the price two weeks ago. Some of the lorry drivers are too afraid to come. They say the village is cursed, or they are with family who are sick and can't go out. With no cooking gas, you can't use the gas stove, so the house is filled with thick smoke from the fireplace. There is no chimney. You wonder if this is why there are other people coughing, because of the smoke from the cooking fire, not the virus. An aid worker who came to the village with the stoves, said that more people die from breathing wood smoke in their homes than from breathing gases from cars. But the way it is looking, either the virus will kill us elders or we will starve.

Someone has started making chairs in the village. The hostel they ran for the tourists has shuttered for the time being, and no-one knows when the white people will start coming again to go on safaris and bathe in big chlorinated swimming pools. It is a shame they are not bringing business to the village anymore. Some even paid a visit to your hair salon. They come when they want, but when anything scares them, they run! Like the gazelle that come and go with the season. Or the locusts, that come when there is bounty and go when there is no more to be eat.

The locusts are bad this year. They have eaten the fields belonging to two whole villages not far away. And there are more coming according to the radio.

How will we make it through the dry season? 

The young men, who came back to the village when they lost their jobs, are going  out to gather firewood, you don't know where they found it. They head along the main road north and come back every two hours with huge bales bumping up and down the dirt roads on the back of the motorcycles. The national park is north of the village, but cutting wood there, as it is forbidden. They wouldn't risk it, would they? 

There is a man who came and said he would buy the wood, and gave a higher price than the man making chairs. Maybe they will make a living from the wood? But what if the ranger stops them? Or if they are stopped by corrupt police, or if the few trees are all cut down ? No, no, don't ask these questions. All will be fine, I hope.

### Why is forest change important?
While there has reductions in air and noise pollution have occurred as a result of COVID-19, these effects can be temporary and are all too easily reversed if transport and industrial activity does not change. Deforestation can have long-lasting impacts because carbon dioxide release from burning of wood has much slower but more persistent effects on climate, and it can take much longer timescales to restore soil carbon within regions affected. We will not even mention the complex issues surrounding inequality, politics, and ownership that might be an underlying driver of environmental damage in low and middle-income countries.

### Methodology

The live data dashboard draws the latest data from Global Forest Watch on deforestation around the world. The data is produced by automatic classification of data from the NASA Landsat 8 satellite (NASA, 2013) to determine changes in forest cover by the Global Forest Watch system (Hansen et al, 2013).

We then plot this against the cumulative number of cases of COVID in a given country, with daily data pulled from the European Centre for Disease Control: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide

We smooth the data for clarity when plotting

All the code is publicly available and can be found as a live version hosted on Google Colabatory, and on [GitHub](https://github.com/tur-ium/COVIDeforestAlert/).


#### Troubleshooting

If the Live Code doesn't run, and you know Python download [Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) (Google sign in required, we do not log who accesses), download the [notebook](COVIDeforestAlert.ipynb) and run the notebook on your own machine.

OR get in touch, arthurdo on rocket chat, arthurdo [at] pm [dot the dot] me

### Thanks

Our thanks go to Mary Allen of Practical Action, based in Mali, for sharing her advice and experience in Sub-Saharan Africa. Without her we would probably have overlooked remittances and the importance to local people.
