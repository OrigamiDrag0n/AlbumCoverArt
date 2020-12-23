# Album Cover Art
Mathematica code creating tiling of album covers proportional to number of listens using <a href = "last.fm">LastFM</a> data! Enjoy!

<img src = "https://i.imgur.com/WR1bLCA.png" alt = "my albums of the year 2020!"/>

## Usage of the code (version 1, *slow* - will be in need of improvement)

To create your chart, execute 

```
myChart = collage[username_, n_] (*creates proportional chart for your top n artists, n < 50*)
```
(for example, the above image was created with `collage["origamidrag0n", 50]`).

Text was added using the <a href = https://www.gimp.org/">GIMP editor</a> - but any similar program will also do. Will work on adding this automatically, and improving efficiency, in future.

