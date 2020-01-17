Backend API for Net Income Calculator


Tax and Rent Information about a city can be attained by making a `post` request to `/getdata`.

Example Request:
```json
{
    "salary": "100000",
    "state": "Colorado",
    "cityValue": "colorado-springs"
}
```

City Values (First Value): 
```
albuquerque - Albuquerque, NM
anaheim - Anaheim, CA
anchorage - Anchorage, AK
arlington-tx - Arlington, TX
atlanta - Atlanta, GA
aurora-co - Aurora, CO
austin - Austin, TX
bakersfield - Bakersfield, CA
baltimore - Baltimore, MD
birmingham - Birmingham, AL
boston - Boston, MA
buffalo - Buffalo, NY
chandler - Chandler, AZ
charlotte - Charlotte, NC
chicago - Chicago, IL
cincinnati - Cincinnati, OH
cleveland - Cleveland, OH
colorado-springs - Colorado Springs, CO
columbus-oh - Columbus, OH
corpus-christi - Corpus Christi, TX
dallas - Dallas, TX
denver - Denver, CO
detroit - Detroit, MI
el-paso - El Paso, TX
fort-wayne - Fort Wayne, IN
fort-worth - Fort Worth, TX
fresno - Fresno, CA
glendale-az - Glendale, AZ
greensboro - Greensboro, NC
henderson - Henderson, NV
honolulu - Honolulu, HI
houston - Houston, TX
indianapolis - Indianapolis, IN
jacksonville-fl - Jacksonville, FL
jersey-city - Jersey City, NJ
kansas-city-mo - Kansas City, MO
las-vegas - Las Vegas, NV
lexington - Lexington, KY
lincoln - Lincoln, NE
long-beach - Long Beach, CA
los-angeles - Los Angeles, CA
louisville - Louisville, KY
memphis - Memphis, TN
mesa - Mesa, AZ
miami - Miami, FL
milwaukee - Milwaukee, WI
minneapolis - Minneapolis, MN
nashville - Nashville, TN
new-orleans - New Orleans, LA
new-york - New York, NY
newark - Newark, NJ
norfolk - Norfolk, VA
oakland - Oakland, CA
oklahoma-city - Oklahoma City, OK
omaha - Omaha, NE
philadelphia - Philadelphia, PA
phoenix - Phoenix, AZ
pittsburgh - Pittsburgh, PA
plano - Plano, TX
portland-or - Portland, OR
raleigh - Raleigh, NC
riverside - Riverside, CA
sacramento - Sacramento, CA
san-antonio - San Antonio, TX
san-diego - San Diego, CA
san-francisco - San Francisco, CA
san-jose - San Jose, CA
santa-ana - Santa Ana, CA
scottsdale - Scottsdale, AZ
seattle - Seattle, WA
st-louis - St. Louis, MO
st-paul - St. Paul, MN
st-petersburg - St. Petersburg, FL
stockton - Stockton, CA
tampa - Tampa, FL
toledo - Toledo, OH
tucson - Tucson, AZ
tulsa - Tulsa, OK
virginia-beach - Virginia Beach, VA
washington - Washington, DC
wichita - Wichita, KS
```
