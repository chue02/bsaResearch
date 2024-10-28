# BSA Research Project

How can a defense maximize their EPA in "clutch time"?

# Methodology

## Data Sources

Provided by nflverse.
[Play-py-Play](https://github.com/nflverse/nflverse-data/releases/tag/pbp) data was acquired here while [NGS play-by-play](https://github.com/nflverse/nflverse-data/releases/tag/pbp_participation) data was acquired here.

Any data acquired from the GitHub links will be in the `data/raw` folder while anything we cleaned up will be in other folders of the `data` directory.

## Packages Used in Conda
```
# Name                    Version                   Build  Channel
blas                      1.0                    openblas  
bottleneck                1.3.7           py312ha86b861_0  
brotli                    1.0.9                h80987f9_8  
brotli-bin                1.0.9                h80987f9_8  
bzip2                     1.0.8                h80987f9_6  
ca-certificates           2024.9.24            hca03da5_0  
contourpy                 1.2.0           py312h48ca7d4_0  
cycler                    0.11.0             pyhd3eb1b0_0  
expat                     2.6.3                h313beb8_0  
fonttools                 4.51.0          py312h80987f9_0  
freetype                  2.12.1               h1192e45_0  
joblib                    1.4.2           py312hca03da5_0  
jpeg                      9e                   h80987f9_3  
kiwisolver                1.4.4           py312h313beb8_0  
lcms2                     2.12                 hba8e193_0  
lerc                      3.0                  hc377ac9_0  
libbrotlicommon           1.0.9                h80987f9_8  
libbrotlidec              1.0.9                h80987f9_8  
libbrotlienc              1.0.9                h80987f9_8  
libcxx                    14.0.6               h848a8c0_0  
libdeflate                1.17                 h80987f9_1  
libffi                    3.4.4                hca03da5_1  
libgfortran               5.0.0           11_3_0_hca03da5_28  
libgfortran5              11.3.0              h009349e_28  
libopenblas               0.3.21               h269037a_0  
libpng                    1.6.39               h80987f9_0  
libtiff                   4.5.1                h313beb8_0  
libwebp-base              1.3.2                h80987f9_1  
llvm-openmp               14.0.6               hc6e5704_0  
lz4-c                     1.9.4                h313beb8_1  
matplotlib                3.9.2           py312hca03da5_0  
matplotlib-base           3.9.2           py312h2df2da3_0  
ncurses                   6.4                  h313beb8_0  
numexpr                   2.8.7           py312h0f3ea24_0  
numpy                     1.26.4          py312h7f4fdc5_0  
numpy-base                1.26.4          py312he047099_0  
openjpeg                  2.5.2                h54b8e55_0  
openssl                   3.0.15               h80987f9_0  
packaging                 24.1            py312hca03da5_0  
pandas                    2.2.2           py312hd77ebd4_0  
pillow                    10.4.0          py312h80987f9_0  
pip                       24.2            py312hca03da5_0  
pybind11-abi              5                    hd3eb1b0_0  
pyparsing                 3.1.2           py312hca03da5_0  
python                    3.12.7               h99e199e_0  
python-dateutil           2.9.0post0      py312hca03da5_2  
python-tzdata             2023.3             pyhd3eb1b0_0  
pytz                      2024.1          py312hca03da5_0  
readline                  8.2                  h1a28f6b_0  
scikit-learn              1.5.1           py312hd77ebd4_0  
scipy                     1.13.1          py312ha409365_0  
seaborn                   0.13.2          py312hca03da5_0  
setuptools                72.1.0          py312hca03da5_0  
six                       1.16.0             pyhd3eb1b0_1  
sqlite                    3.45.3               h80987f9_0  
threadpoolctl             3.5.0           py312h989b03a_0  
tk                        8.6.14               h6ba3021_0  
tornado                   6.4.1           py312h80987f9_0  
tzdata                    2024b                h04d1e81_0  
unicodedata2              15.1.0          py312h80987f9_0  
wheel                     0.44.0          py312hca03da5_0  
xz                        5.4.6                h80987f9_1  
zlib                      1.2.13               h18a0788_1  
zstd                      1.5.6                hfb09047_0  
```

# TODO:

- [ ] Clean dataframes
- [ ] Figure out how to JOIN pbp and pbp_participation dataframes
  - Probably based on game id?
- [ ] Create zero-sum matrix using Tableau and EPA
  - [ ] Also create a way to paramterize this by year
