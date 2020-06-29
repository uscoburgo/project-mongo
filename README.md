# Finding the HQ for my gaming company

![alt text](https://www.google.com/url?sa=i&url=https%3A%2F%2Fits509.com%2Fservices%2Fmobile-application%2Fgeolocalization%2F&psig=AOvVaw2WsGuLWUCN9meepClj2VKJ&ust=1593554313827000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJjwysiCqOoCFQAAAAAdAAAAABAD/to/img.png)

The goal of this project was to find the ideal location for a company based on predefined preferences:

- [x] Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design. 
- [x] 30% of the company have at least 1 child.
- [x] Developers like to be near successful tech startups that have raised at least 1 Million dollars.
- [x] Executives like Starbucks A LOT. Ensure there's a starbucks not to far.
- [ ] Account managers need to travel a lot
- [ ] All people in the company have between 25 and 40 years, give them some place to go to party.
- [x] The CEO is Vegan
- [ ] If you want to make the maintenance guy happy, a basketball stadium must be around 10 Km.
- [x] The office dog "Pepe" needs a hairdresser every month. Ensure there's one not too far away.

I have decided to not take care of airports because **COVID has affected business travel** are less relevant now. Places for party are not necessary because all the employees are extremely hard working and **hate partying** :)

## Let's take a look at the preferences I have fulfilled:

1. Designers like to go to design talks and share knowledge. There must be some nearby companies that also do design.
2. Developers like to be near successful tech startups that have raised at least 1 Million dollars.

To take care of these 2 requirements, I have used data cleaning and data wrangling. CHECK `choosingCity.ipynb` where I check the Crunchbase database to find what city is the most appropriate.

3. 30% of the company have at least 1 child.
4. Executives like Starbucks A LOT. Ensure there's a starbucks not to far.
5. The CEO is Vegan
6. The office dog "Pepe" needs a hairdresser every month. Ensure there's one not too far away.

To take care of these I have used the Google Places API to find every place that's requested, in San Francisco. Checkout `API_SanFrancisco.ipynb`. 

## Displaying the map 

In `FindingCoordinate.ipynb`, I was supposed to create numerous random coordinates that spread around San Francisco, and find the one coordinate where distances are optimized and every place(Starbucks etc...) is the closest it can be from the HQ(the random coordinate). However I wasn't able to accomplish this. 

​
