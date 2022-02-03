# COVID19-US-Case-Map
Visualizing US covid cases

## Quickstart
Requires Python 3.9+

```
%pip install folium
%pip install pandas
%pip install sodapy
```

Also requires [geopandas](https://geopandas.org/getting_started/install.html)
`conda install geopandas`

## API 
The API used is provided by CDC and powered by Socrata.
[API can be found here.](https://dev.socrata.com/foundry/data.cdc.gov/9mfq-cb36)

API key stored in apikey.json held in same directory as the notebook

```
{
	"apikey":"api key goes here"
}
```

## Example Image

![Example](https://i.imgur.com/J0ufuYa.png)
