## Dataset characteristics

day.csv have the following fields:
- instant: record index
- dteday : date
- season : season (1:winter, 2:spring, 3:summer, 4:fall)
- yr : year (0: 2018, 1:2019)
- mnth : month ( 1 to 12)
- holiday : weather day is a holiday or not (extracted from [holiday schedule](https://dchr.dc.gov/page/holiday-schedules))
- weekday : day of the week
- workingday : if day is either weekend or a holiday, this is 0, otherwise this is 1.
- weathersit : 
  - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : temperature in Celsius
- atemp: feeling temperature in Celsius
- hum: humidity
- windspeed: wind speed (probably mph)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered
	

## License

Use of this dataset in publications must be cited to the following publication:

`[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3`

```java script
@article{
	year={2013},
	issn={'2192-6352'},
	journal={'Progress in Artificial Intelligence'},
	doi={'10.1007/s13748-013-0040-3'},
	title={'Event labeling combining ensemble detectors and background knowledge'},
	url={'http://dx.doi.org/10.1007/s13748-013-0040-3'},
	publisher={'Springer Berlin Heidelberg'},
	keywords={'Event labeling; Event detection; Ensemble learning; Background knowledge'},
	author={'Fanaee-T, Hadi and Gama, Joao'},
	pages={'1-15'}
}
```

## Contact
	
For further information about this dataset please contact Hadi Fanaee-T (`hadi.fanaee@fe.up.pt`)
