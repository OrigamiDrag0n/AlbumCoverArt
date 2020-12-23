# Album Cover Art
Mathematica code creating tiling of album covers proportional to number of listens using last.fm data! Enjoy!

![My albums of the 2020!]("https://imgur.com/a/nTp1OHQ")

## Usage of the code (version 1, *slow* - will be in need of improvement)

To create your chart, execute 

```
myChart = collage[username_, n_] (*creates proportional chart for your top n artists, n < 50*)
```
(for example, the above image was created with `collage["origamidrag0n", 50]`).

