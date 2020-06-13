# Space Deno Project

## SpaceX
#### Run spacex.ts
> deno run --allow-net=api.spacexdata.com spacex.ts 

## Kepler Mission
<p>The script reads a .csv file provided by NASA on Kepler mission, with thousands of exoplanets found. After parsing the file, the program applies a series of filters based on recent studies, to evaluate if the exoplanet might contain life.</p>
<p>The <em>allow_read</em> flag allows the script to read the .csv file.</p>

#### Run kepler.ts
>deno run --allow-read kepler.ts
