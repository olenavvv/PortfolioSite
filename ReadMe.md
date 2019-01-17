My project is site portfolio for photographer where he or she can exibit the photos and additional information about himself or herself.
The site includes several pages: Home, About, Gallery (with exapmles of works), Contact( where is form for communication), Login (for making registration), and Weather (where user can see forecast for planning shoot).

Basic description of each module:
1) I explored and used Bootstrap libraries for my site.
2) I used Date objects for  recieving date of forecast that user choosed. User can see forecast for 5 next days. So, he or she chooses date forecast in select option. After that, according choise of user function dateOfForecast return date of desired day in format string.Than the string of date appears in table after click.
3) I made Ajax request, namely: 
- created access key to OpenWeatherMap, section: 5 day/3 hours forecast
- did request indicating : city, metric system, api key and recieved response in format json
- after parsing json string, I see necessary information in console and add code to retrieve data that I need
- print the output and icon  in my HTML page in table.