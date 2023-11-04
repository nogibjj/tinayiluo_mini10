The operation is load data

The truncated output is: 

|    |   page_id | name   | urlslug   | ID   | ALIGN   | EYE   | HAIR   | SEX   | GSM   | ALIVE   |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------|:----------|:-----|:--------|:------|:-------|:------|:------|:--------|--------------:|:-------------------|-------:|
|  0 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  1 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  2 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  3 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  4 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  5 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  6 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  7 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  8 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |
|  9 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan |

The operation is describe data

The truncated output is: 

|    | summary   |   page_id | name        | urlslug            | ID                    | ALIGN                  | EYE                        | HAIR                                | SEX                                                     | GSM                                    | ALIVE                                                               |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|:----------|----------:|:------------|:-------------------|:----------------------|:-----------------------|:---------------------------|:------------------------------------|:--------------------------------------------------------|:---------------------------------------|:--------------------------------------------------------------------|--------------:|:-------------------|-------:|
|  0 | count     |         0 | 70          | 63                 | 45                    | 10                     | 9                          | 3                                   | 2                                                       | 1                                      | 1                                                                   |             0 | 1                  |      0 |
|  1 | mean      |           |             |                    |                       |                        |                            |                                     |                                                         |                                        |                                                                     |               |                    |        |
|  2 | stddev    |           |             |                    |                       |                        |                            |                                     |                                                         |                                        |                                                                     |               |                    |        |
|  3 | min       |           | Ebooks      | Webinars           | Ebooks                | Webinars&quot;         | "currentUserCanPush":false | Ebooks                              | Webinars;&quot;}" href="https://resources.github.com/"> | "createdAt":"2014-03-17T13:49:17.000Z" | "ownerAvatar":"https://avatars.githubusercontent.com/u/6267336?v=4" |               | "private":false    |        |
|  4 | max       |           | source-code | geojson_azure_maps | image_metric_tracking | turbo_experiment_risky | sample_network_conn_type   | "upload_manifest_status"]}</script> | "isEmpty":false                                         | "createdAt":"2014-03-17T13:49:17.000Z" | "ownerAvatar":"https://avatars.githubusercontent.com/u/6267336?v=4" |               | "private":false    |        |

The operation is query data

The query is SELECT YEAR, COUNT(*) AS character_count FROM characters GROUP BY YEAR ORDER BY YEAR

The truncated output is: 

|    |   YEAR |   character_count |
|---:|-------:|------------------:|
|  0 |    nan |              1066 |

The operation is transform data

The truncated output is: 

|    |   page_id | name   | urlslug   | ID   | ALIGN   | EYE   | HAIR   | SEX   | GSM   | ALIVE   |   APPEARANCES | FIRST APPEARANCE   |   YEAR | Character_Category   |
|---:|----------:|:-------|:----------|:-----|:--------|:------|:-------|:------|:------|:--------|--------------:|:-------------------|-------:|:---------------------|
|  0 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  1 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  2 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  3 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  4 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  5 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  6 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  7 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  8 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |
|  9 |       nan |        |           |      |         |       |        |       |       |         |           nan |                    |    nan | Other                |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is describe data

The truncated output is: 

|    | summary   |   page_id | name                   | urlslug                        | ID               | ALIGN              | EYE         | HAIR       | SEX                    | GSM                   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |      YEAR |
|---:|:----------|----------:|:-----------------------|:-------------------------------|:-----------------|:-------------------|:------------|:-----------|:-----------------------|:----------------------|:--------------------|--------------:|:-------------------|----------:|
|  0 | count     |      6896 | 6896                   | 6896                           | 4883             | 6295               | 3268        | 4622       | 6771                   | 64                    | 6893                |     6541      | 6827               | 6827      |
|  1 | mean      |    147441 |                        |                                |                  |                    |             |            |                        |                       |                     |       23.6251 | 1990.7430555555557 | 1989.77   |
|  2 | stddev    |    108389 |                        |                                |                  |                    |             |            |                        |                       |                     |       87.3785 | 5.9528996610487805 |   16.8242 |
|  3 | min       |      1380 | 3g4 (New Earth)        | \/wiki\/3g4_(New_Earth)        | Identity Unknown | Bad Characters     | Amber Eyes  | Black Hair | Female Characters      | Bisexual Characters   | Deceased Characters |        1      | 1935, October      | 1935      |
|  4 | max       |    404010 | Zzlrrrzzzm (New Earth) | \/wiki\/Zzlrrrzzzm_(New_Earth) | Secret Identity  | Reformed Criminals | Yellow Eyes | White Hair | Transgender Characters | Homosexual Characters | Living Characters   |     3093      | 2013, October      | 2013      |

The operation is query data

The query is SELECT YEAR, COUNT(*) AS character_count FROM characters GROUP BY YEAR ORDER BY YEAR

The truncated output is: 

|    |   YEAR |   character_count |
|---:|-------:|------------------:|
|  0 |    nan |                69 |
|  1 |   1935 |                 1 |
|  2 |   1936 |                 9 |
|  3 |   1937 |                 4 |
|  4 |   1938 |                10 |
|  5 |   1939 |                18 |
|  6 |   1940 |                64 |
|  7 |   1941 |                61 |
|  8 |   1942 |                52 |
|  9 |   1943 |                14 |
| 10 |   1944 |                15 |
| 11 |   1945 |                 7 |
| 12 |   1946 |                 9 |
| 13 |   1947 |                20 |
| 14 |   1948 |                20 |
| 15 |   1949 |                 6 |
| 16 |   1950 |                 9 |
| 17 |   1951 |                12 |
| 18 |   1952 |                 5 |
| 19 |   1953 |                 1 |
| 20 |   1954 |                 7 |
| 21 |   1955 |                12 |
| 22 |   1956 |                13 |
| 23 |   1957 |                13 |
| 24 |   1958 |                15 |
| 25 |   1959 |                34 |
| 26 |   1960 |                39 |
| 27 |   1961 |                50 |
| 28 |   1962 |                42 |
| 29 |   1963 |                40 |
| 30 |   1964 |                31 |
| 31 |   1965 |                50 |
| 32 |   1966 |                61 |
| 33 |   1967 |                56 |
| 34 |   1968 |                61 |
| 35 |   1969 |                23 |
| 36 |   1970 |                28 |
| 37 |   1971 |                65 |
| 38 |   1972 |                61 |
| 39 |   1973 |                20 |
| 40 |   1974 |                17 |
| 41 |   1975 |                39 |
| 42 |   1976 |                45 |
| 43 |   1977 |                52 |
| 44 |   1978 |                60 |
| 45 |   1979 |                29 |
| 46 |   1980 |                36 |
| 47 |   1981 |               119 |
| 48 |   1982 |               111 |
| 49 |   1983 |               161 |
| 50 |   1984 |               141 |
| 51 |   1985 |               115 |
| 52 |   1986 |               132 |
| 53 |   1987 |               254 |
| 54 |   1988 |               286 |
| 55 |   1989 |               266 |
| 56 |   1990 |               175 |
| 57 |   1991 |               145 |
| 58 |   1992 |               178 |
| 59 |   1993 |               209 |
| 60 |   1994 |               230 |
| 61 |   1995 |               172 |
| 62 |   1996 |               188 |
| 63 |   1997 |               189 |
| 64 |   1998 |               143 |
| 65 |   1999 |               179 |
| 66 |   2000 |               152 |
| 67 |   2001 |                99 |
| 68 |   2002 |               115 |
| 69 |   2003 |               103 |
| 70 |   2004 |               102 |
| 71 |   2005 |               159 |
| 72 |   2006 |               303 |
| 73 |   2007 |               188 |
| 74 |   2008 |               211 |
| 75 |   2009 |               226 |
| 76 |   2010 |               279 |
| 77 |   2011 |               155 |
| 78 |   2012 |                 5 |
| 79 |   2013 |                 1 |

The operation is transform data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR | Character_Category   |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|:---------------------|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 | Hero                 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 | Hero                 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 | Hero                 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 | Hero                 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 | Hero                 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 | Hero                 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 | Hero                 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 | Hero                 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 | Hero                 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 | Hero                 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is describe data

The truncated output is: 

|    | summary   |   page_id | name                   | urlslug                        | ID               | ALIGN              | EYE         | HAIR       | SEX                    | GSM                   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |      YEAR |
|---:|:----------|----------:|:-----------------------|:-------------------------------|:-----------------|:-------------------|:------------|:-----------|:-----------------------|:----------------------|:--------------------|--------------:|:-------------------|----------:|
|  0 | count     |      6896 | 6896                   | 6896                           | 4883             | 6295               | 3268        | 4622       | 6771                   | 64                    | 6893                |     6541      | 6827               | 6827      |
|  1 | mean      |    147441 |                        |                                |                  |                    |             |            |                        |                       |                     |       23.6251 | 1990.7430555555557 | 1989.77   |
|  2 | stddev    |    108389 |                        |                                |                  |                    |             |            |                        |                       |                     |       87.3785 | 5.9528996610487805 |   16.8242 |
|  3 | min       |      1380 | 3g4 (New Earth)        | \/wiki\/3g4_(New_Earth)        | Identity Unknown | Bad Characters     | Amber Eyes  | Black Hair | Female Characters      | Bisexual Characters   | Deceased Characters |        1      | 1935, October      | 1935      |
|  4 | max       |    404010 | Zzlrrrzzzm (New Earth) | \/wiki\/Zzlrrrzzzm_(New_Earth) | Secret Identity  | Reformed Criminals | Yellow Eyes | White Hair | Transgender Characters | Homosexual Characters | Living Characters   |     3093      | 2013, October      | 2013      |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is query data

The query is SELECT * FROM COMIC_CHARACTERS WHERE YEAR = 1939

The truncated output is: 

|    |   page_id | name                          | urlslug                               | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:------------------------------|:--------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:--------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)          | \/wiki\/Batman_(Bruce_Wayne)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |          3093 | 1939, May          |   1939 |
|  1 |      1981 | Wesley Dodds (New Earth)      | \/wiki\/Wesley_Dodds_(New_Earth)      | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Deceased Characters |           391 | 1939, April        |   1939 |
|  2 |      7518 | Abigail Hunkel (New Earth)    | \/wiki\/Abigail_Hunkel_(New_Earth)    | Secret Identity | Good Characters | Black Eyes | Brown Hair | Female Characters |       | Living Characters   |            79 | 1939, June         |   1939 |
|  3 |     41263 | Ultra-Humanite (New Earth)    | \/wiki\/Ultra-Humanite_(New_Earth)    | Secret Identity |                 | Red Eyes   | White Hair | Male Characters   |       | Living Characters   |            74 | 1939, June         |   1939 |
|  4 |      6968 | Hop Harrigan (New Earth)      | \/wiki\/Hop_Harrigan_(New_Earth)      | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters   |            68 | 1939, April        |   1939 |
|  5 |     52340 | Scribbly Jibbet (New Earth)   | \/wiki\/Scribbly_Jibbet_(New_Earth)   | Public Identity | Good Characters |            | Black Hair | Male Characters   |       | Living Characters   |            64 | 1939, April        |   1939 |
|  6 |     18907 | Martha Roberts (New Earth)    | \/wiki\/Martha_Roberts_(New_Earth)    | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Female Characters |       | Deceased Characters |            60 | 1939, December     |   1939 |
|  7 |    139909 | Mortimer Jibbet (New Earth)   | \/wiki\/Mortimer_Jibbet_(New_Earth)   | Secret Identity | Good Characters | Brown Eyes | Black Hair | Male Characters   |       | Living Characters   |            49 | 1939, April        |   1939 |
|  8 |    139914 | Amelia Hunkel (New Earth)     | \/wiki\/Amelia_Hunkel_(New_Earth)     | Secret Identity | Good Characters |            |            | Female Characters |       | Living Characters   |            47 | 1939, June         |   1939 |
|  9 |    200072 | Hugh Hazzard (New Earth)      | \/wiki\/Hugh_Hazzard_(New_Earth)      | Secret Identity | Good Characters |            |            | Male Characters   |       | Living Characters   |            28 | 1939, August       |   1939 |
| 10 |     42002 | Karl Hellfern (New Earth)     | \/wiki\/Karl_Hellfern_(New_Earth)     | Secret Identity | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |            23 | 1939, July         |   1939 |
| 11 |      8116 | Leslie Humphries (New Earth)  | \/wiki\/Leslie_Humphries_(New_Earth)  |                 | Good Characters |            | Black Hair | Male Characters   |       | Deceased Characters |            19 | 1939, July         |   1939 |
| 12 |     17886 | Julie Madison (New Earth)     | \/wiki\/Julie_Madison_(New_Earth)     | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters   |            18 | 1939, September    |   1939 |
| 13 |     61926 | Niccolai Tepes (New Earth)    | \/wiki\/Niccolai_Tepes_(New_Earth)    | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Male Characters   |       | Deceased Characters |            14 | 1939, September    |   1939 |
| 14 |    272889 | Dala (New Earth)              | \/wiki\/Dala_(New_Earth)              | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Female Characters |       | Living Characters   |            13 | 1939, October      |   1939 |
| 15 |    142846 | Gary Concord, Jr. (New Earth) | \/wiki\/Gary_Concord,_Jr._(New_Earth) |                 | Good Characters |            |            | Male Characters   |       | Living Characters   |            13 | 1939, November     |   1939 |
| 16 |    181737 | Darrell Dane (New Earth)      | \/wiki\/Darrell_Dane_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |            12 | 1939, December     |   1939 |
| 17 |    382447 | Jabah (New Earth)             | \/wiki\/Jabah_(New_Earth)             |                 | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |             2 | 1939, July         |   1939 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is transform data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR | Character_Category   |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|:---------------------|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 | Hero                 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 | Hero                 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 | Hero                 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 | Hero                 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 | Hero                 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 | Hero                 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 | Hero                 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 | Hero                 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 | Hero                 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 | Hero                 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is describe data

The truncated output is: 

|    | summary   |   page_id | name                   | urlslug                        | ID               | ALIGN              | EYE         | HAIR       | SEX                    | GSM                   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |      YEAR |
|---:|:----------|----------:|:-----------------------|:-------------------------------|:-----------------|:-------------------|:------------|:-----------|:-----------------------|:----------------------|:--------------------|--------------:|:-------------------|----------:|
|  0 | count     |      6896 | 6896                   | 6896                           | 4883             | 6295               | 3268        | 4622       | 6771                   | 64                    | 6893                |     6541      | 6827               | 6827      |
|  1 | mean      |    147441 |                        |                                |                  |                    |             |            |                        |                       |                     |       23.6251 | 1990.7430555555557 | 1989.77   |
|  2 | stddev    |    108389 |                        |                                |                  |                    |             |            |                        |                       |                     |       87.3785 | 5.9528996610487805 |   16.8242 |
|  3 | min       |      1380 | 3g4 (New Earth)        | \/wiki\/3g4_(New_Earth)        | Identity Unknown | Bad Characters     | Amber Eyes  | Black Hair | Female Characters      | Bisexual Characters   | Deceased Characters |        1      | 1935, October      | 1935      |
|  4 | max       |    404010 | Zzlrrrzzzm (New Earth) | \/wiki\/Zzlrrrzzzm_(New_Earth) | Secret Identity  | Reformed Criminals | Yellow Eyes | White Hair | Transgender Characters | Homosexual Characters | Living Characters   |     3093      | 2013, October      | 2013      |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is query data

The query is SELECT * FROM COMIC_CHARACTERS WHERE YEAR = 1939

The truncated output is: 

|    |   page_id | name                          | urlslug                               | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:------------------------------|:--------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:--------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)          | \/wiki\/Batman_(Bruce_Wayne)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |          3093 | 1939, May          |   1939 |
|  1 |      1981 | Wesley Dodds (New Earth)      | \/wiki\/Wesley_Dodds_(New_Earth)      | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Deceased Characters |           391 | 1939, April        |   1939 |
|  2 |      7518 | Abigail Hunkel (New Earth)    | \/wiki\/Abigail_Hunkel_(New_Earth)    | Secret Identity | Good Characters | Black Eyes | Brown Hair | Female Characters |       | Living Characters   |            79 | 1939, June         |   1939 |
|  3 |     41263 | Ultra-Humanite (New Earth)    | \/wiki\/Ultra-Humanite_(New_Earth)    | Secret Identity |                 | Red Eyes   | White Hair | Male Characters   |       | Living Characters   |            74 | 1939, June         |   1939 |
|  4 |      6968 | Hop Harrigan (New Earth)      | \/wiki\/Hop_Harrigan_(New_Earth)      | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters   |            68 | 1939, April        |   1939 |
|  5 |     52340 | Scribbly Jibbet (New Earth)   | \/wiki\/Scribbly_Jibbet_(New_Earth)   | Public Identity | Good Characters |            | Black Hair | Male Characters   |       | Living Characters   |            64 | 1939, April        |   1939 |
|  6 |     18907 | Martha Roberts (New Earth)    | \/wiki\/Martha_Roberts_(New_Earth)    | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Female Characters |       | Deceased Characters |            60 | 1939, December     |   1939 |
|  7 |    139909 | Mortimer Jibbet (New Earth)   | \/wiki\/Mortimer_Jibbet_(New_Earth)   | Secret Identity | Good Characters | Brown Eyes | Black Hair | Male Characters   |       | Living Characters   |            49 | 1939, April        |   1939 |
|  8 |    139914 | Amelia Hunkel (New Earth)     | \/wiki\/Amelia_Hunkel_(New_Earth)     | Secret Identity | Good Characters |            |            | Female Characters |       | Living Characters   |            47 | 1939, June         |   1939 |
|  9 |    200072 | Hugh Hazzard (New Earth)      | \/wiki\/Hugh_Hazzard_(New_Earth)      | Secret Identity | Good Characters |            |            | Male Characters   |       | Living Characters   |            28 | 1939, August       |   1939 |
| 10 |     42002 | Karl Hellfern (New Earth)     | \/wiki\/Karl_Hellfern_(New_Earth)     | Secret Identity | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |            23 | 1939, July         |   1939 |
| 11 |      8116 | Leslie Humphries (New Earth)  | \/wiki\/Leslie_Humphries_(New_Earth)  |                 | Good Characters |            | Black Hair | Male Characters   |       | Deceased Characters |            19 | 1939, July         |   1939 |
| 12 |     17886 | Julie Madison (New Earth)     | \/wiki\/Julie_Madison_(New_Earth)     | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters   |            18 | 1939, September    |   1939 |
| 13 |     61926 | Niccolai Tepes (New Earth)    | \/wiki\/Niccolai_Tepes_(New_Earth)    | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Male Characters   |       | Deceased Characters |            14 | 1939, September    |   1939 |
| 14 |    272889 | Dala (New Earth)              | \/wiki\/Dala_(New_Earth)              | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Female Characters |       | Living Characters   |            13 | 1939, October      |   1939 |
| 15 |    142846 | Gary Concord, Jr. (New Earth) | \/wiki\/Gary_Concord,_Jr._(New_Earth) |                 | Good Characters |            |            | Male Characters   |       | Living Characters   |            13 | 1939, November     |   1939 |
| 16 |    181737 | Darrell Dane (New Earth)      | \/wiki\/Darrell_Dane_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |            12 | 1939, December     |   1939 |
| 17 |    382447 | Jabah (New Earth)             | \/wiki\/Jabah_(New_Earth)             |                 | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |             2 | 1939, July         |   1939 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is transform data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR | Character_Category   |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|:---------------------|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 | Hero                 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 | Hero                 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 | Hero                 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 | Hero                 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 | Hero                 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 | Hero                 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 | Hero                 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 | Hero                 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 | Hero                 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 | Hero                 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is describe data

The truncated output is: 

|    | summary   |   page_id | name                   | urlslug                        | ID               | ALIGN              | EYE         | HAIR       | SEX                    | GSM                   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |      YEAR |
|---:|:----------|----------:|:-----------------------|:-------------------------------|:-----------------|:-------------------|:------------|:-----------|:-----------------------|:----------------------|:--------------------|--------------:|:-------------------|----------:|
|  0 | count     |      6896 | 6896                   | 6896                           | 4883             | 6295               | 3268        | 4622       | 6771                   | 64                    | 6893                |     6541      | 6827               | 6827      |
|  1 | mean      |    147441 |                        |                                |                  |                    |             |            |                        |                       |                     |       23.6251 | 1990.7430555555557 | 1989.77   |
|  2 | stddev    |    108389 |                        |                                |                  |                    |             |            |                        |                       |                     |       87.3785 | 5.9528996610487805 |   16.8242 |
|  3 | min       |      1380 | 3g4 (New Earth)        | \/wiki\/3g4_(New_Earth)        | Identity Unknown | Bad Characters     | Amber Eyes  | Black Hair | Female Characters      | Bisexual Characters   | Deceased Characters |        1      | 1935, October      | 1935      |
|  4 | max       |    404010 | Zzlrrrzzzm (New Earth) | \/wiki\/Zzlrrrzzzm_(New_Earth) | Secret Identity  | Reformed Criminals | Yellow Eyes | White Hair | Transgender Characters | Homosexual Characters | Living Characters   |     3093      | 2013, October      | 2013      |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is query data

The query is SELECT * FROM COMIC_CHARACTERS WHERE YEAR = 1939

The truncated output is: 

|    |   page_id | name                          | urlslug                               | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE               |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:------------------------------|:--------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:--------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)          | \/wiki\/Batman_(Bruce_Wayne)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |          3093 | 1939, May          |   1939 |
|  1 |      1981 | Wesley Dodds (New Earth)      | \/wiki\/Wesley_Dodds_(New_Earth)      | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Deceased Characters |           391 | 1939, April        |   1939 |
|  2 |      7518 | Abigail Hunkel (New Earth)    | \/wiki\/Abigail_Hunkel_(New_Earth)    | Secret Identity | Good Characters | Black Eyes | Brown Hair | Female Characters |       | Living Characters   |            79 | 1939, June         |   1939 |
|  3 |     41263 | Ultra-Humanite (New Earth)    | \/wiki\/Ultra-Humanite_(New_Earth)    | Secret Identity |                 | Red Eyes   | White Hair | Male Characters   |       | Living Characters   |            74 | 1939, June         |   1939 |
|  4 |      6968 | Hop Harrigan (New Earth)      | \/wiki\/Hop_Harrigan_(New_Earth)      | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters   |            68 | 1939, April        |   1939 |
|  5 |     52340 | Scribbly Jibbet (New Earth)   | \/wiki\/Scribbly_Jibbet_(New_Earth)   | Public Identity | Good Characters |            | Black Hair | Male Characters   |       | Living Characters   |            64 | 1939, April        |   1939 |
|  6 |     18907 | Martha Roberts (New Earth)    | \/wiki\/Martha_Roberts_(New_Earth)    | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Female Characters |       | Deceased Characters |            60 | 1939, December     |   1939 |
|  7 |    139909 | Mortimer Jibbet (New Earth)   | \/wiki\/Mortimer_Jibbet_(New_Earth)   | Secret Identity | Good Characters | Brown Eyes | Black Hair | Male Characters   |       | Living Characters   |            49 | 1939, April        |   1939 |
|  8 |    139914 | Amelia Hunkel (New Earth)     | \/wiki\/Amelia_Hunkel_(New_Earth)     | Secret Identity | Good Characters |            |            | Female Characters |       | Living Characters   |            47 | 1939, June         |   1939 |
|  9 |    200072 | Hugh Hazzard (New Earth)      | \/wiki\/Hugh_Hazzard_(New_Earth)      | Secret Identity | Good Characters |            |            | Male Characters   |       | Living Characters   |            28 | 1939, August       |   1939 |
| 10 |     42002 | Karl Hellfern (New Earth)     | \/wiki\/Karl_Hellfern_(New_Earth)     | Secret Identity | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |            23 | 1939, July         |   1939 |
| 11 |      8116 | Leslie Humphries (New Earth)  | \/wiki\/Leslie_Humphries_(New_Earth)  |                 | Good Characters |            | Black Hair | Male Characters   |       | Deceased Characters |            19 | 1939, July         |   1939 |
| 12 |     17886 | Julie Madison (New Earth)     | \/wiki\/Julie_Madison_(New_Earth)     | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters   |            18 | 1939, September    |   1939 |
| 13 |     61926 | Niccolai Tepes (New Earth)    | \/wiki\/Niccolai_Tepes_(New_Earth)    | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Male Characters   |       | Deceased Characters |            14 | 1939, September    |   1939 |
| 14 |    272889 | Dala (New Earth)              | \/wiki\/Dala_(New_Earth)              | Secret Identity | Bad Characters  | Red Eyes   | Black Hair | Female Characters |       | Living Characters   |            13 | 1939, October      |   1939 |
| 15 |    142846 | Gary Concord, Jr. (New Earth) | \/wiki\/Gary_Concord,_Jr._(New_Earth) |                 | Good Characters |            |            | Male Characters   |       | Living Characters   |            13 | 1939, November     |   1939 |
| 16 |    181737 | Darrell Dane (New Earth)      | \/wiki\/Darrell_Dane_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters   |            12 | 1939, December     |   1939 |
| 17 |    382447 | Jabah (New Earth)             | \/wiki\/Jabah_(New_Earth)             |                 | Bad Characters  |            | Black Hair | Male Characters   |       | Living Characters   |             2 | 1939, July         |   1939 |

The operation is load data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 |

The operation is transform data

The truncated output is: 

|    |   page_id | name                           | urlslug                                | ID              | ALIGN           | EYE        | HAIR       | SEX               | GSM   | ALIVE             |   APPEARANCES | FIRST APPEARANCE   |   YEAR | Character_Category   |
|---:|----------:|:-------------------------------|:---------------------------------------|:----------------|:----------------|:-----------|:-----------|:------------------|:------|:------------------|--------------:|:-------------------|-------:|:---------------------|
|  0 |      1422 | Batman (Bruce Wayne)           | \/wiki\/Batman_(Bruce_Wayne)           | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          3093 | 1939, May          |   1939 | Hero                 |
|  1 |     23387 | Superman (Clark Kent)          | \/wiki\/Superman_(Clark_Kent)          | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          2496 | 1986, October      |   1986 | Hero                 |
|  2 |      1458 | Green Lantern (Hal Jordan)     | \/wiki\/Green_Lantern_(Hal_Jordan)     | Secret Identity | Good Characters | Brown Eyes | Brown Hair | Male Characters   |       | Living Characters |          1565 | 1959, October      |   1959 | Hero                 |
|  3 |      1659 | James Gordon (New Earth)       | \/wiki\/James_Gordon_(New_Earth)       | Public Identity | Good Characters | Brown Eyes | White Hair | Male Characters   |       | Living Characters |          1316 | 1987, February     |   1987 | Hero                 |
|  4 |      1576 | Richard Grayson (New Earth)    | \/wiki\/Richard_Grayson_(New_Earth)    | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1237 | 1940, April        |   1940 | Hero                 |
|  5 |      1448 | Wonder Woman (Diana Prince)    | \/wiki\/Wonder_Woman_(Diana_Prince)    | Public Identity | Good Characters | Blue Eyes  | Black Hair | Female Characters |       | Living Characters |          1231 | 1941, December     |   1941 | Hero                 |
|  6 |      1486 | Aquaman (Arthur Curry)         | \/wiki\/Aquaman_(Arthur_Curry)         | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1121 | 1941, November     |   1941 | Hero                 |
|  7 |      1451 | Timothy Drake (New Earth)      | \/wiki\/Timothy_Drake_(New_Earth)      | Secret Identity | Good Characters | Blue Eyes  | Black Hair | Male Characters   |       | Living Characters |          1095 | 1989, August       |   1989 | Hero                 |
|  8 |     71760 | Dinah Laurel Lance (New Earth) | \/wiki\/Dinah_Laurel_Lance_(New_Earth) | Public Identity | Good Characters | Blue Eyes  | Blond Hair | Female Characters |       | Living Characters |          1075 | 1969, November     |   1969 | Hero                 |
|  9 |      1380 | Flash (Barry Allen)            | \/wiki\/Flash_(Barry_Allen)            | Secret Identity | Good Characters | Blue Eyes  | Blond Hair | Male Characters   |       | Living Characters |          1028 | 1956, October      |   1956 | Hero                 |

