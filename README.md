

## Impacts of Ocean Alkalinity Enhancement on the Seasonal Cycle of CO2 Flux and ocean pCO2 in European Waters


A seasonal analysis was performed on five variables, with the objective of defining the impacts of Ocean Alkalinity Enhancementmonthly on their monthly and amplitude cycle. The variables are:

- Alkalinity (mmol/m3)
- pH
- Dissolved Inorganic Carbon (mmol/m3)
- CO2 flux (mol/m2/yr)
- Ocean pCO2 (µatm)

Two reference scenarios are used: SSP1_2.6 (low warming) and SSP3_7.0 (high warming).

The model domain is the European coasts (excluding the Mediterranean and the Baltic seas).

### Repository content

This repository contains:
- 'geomarcode', including: data pre-processing and seasonality analysis for each variable: alkalinity, pH, DIC, CO2 flux, ocean pCO2;
- MSc thesis report (Latex and PDF version);
- MSc thesis presentation (PDF version)


```

## Authors

- [@chiaraciscato](https://github.com/chiaraciscato)


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

