# EDS 222: Statistics - Final Project

## Data

[Data Link](https://portal.edirepository.org/nis/metadataviewer?packageid=knb-lter-msp.11.1)

The Minneapolis-St. Paul Area Long Term Ecological Research Program (MSP LTER) is studying how urban stressors impact the surrounding ecological structure and function. Urban lakes are systems that are heavily impacted by human activities and climate variability. This dataset's goal is to help understand how land-use change and climate affect urban lake bio-geochemistry over time. Parameters of these data include long-term surface water quality measurements of 294 lakes and ponds in the Minneapolis-Saint Paul Seven County Metropolitan Area, Minnesota, USA.

**Model thoughts:**

-   Using a Gamma distribution seems like the best choice for pollution concentrations as a response.

    -   Right skewed data, positive continuous data

**State hypothesis**

-   On average, pollution concentrations in urban Minnesota lakes, increase over time.

**Model in statistical notation**

$$Concentration \sim Gamma(\alpha, \beta) \\ \log(\mu) = \beta_0 + \beta_1 * Time$$

-   Response Family: Gamma

-   Link Function: log()

-   Predictor: Time

-   $H_0$: $\beta_1$ \<= 0

-   $H_1$: $\beta_1$ \> 0
