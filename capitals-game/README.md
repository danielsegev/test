# Capital Departures

A world capitals quiz styled as a boarding pass. Name the capital to board the flight; miss it and you stay in the last city you reached.

Open `index.html` in a browser. No build step or dependencies.

- 194 countries (UN members plus Vatican City), grouped into Africa, Americas, Asia, Europe and Oceania
- Ask country → capital or capital → country
- Pick from 4 options (wrong options come from the same region) or type the answer (accents, "St."/"Saint" and common alternate names are accepted)
- Trips of 10, 20 or every capital
- Tracks score, streak and great-circle km flown between capitals
- Notes on tricky cases (Bolivia, South Africa, Sri Lanka, etc.)
- **Daily Flight:** 5 capitals a day, one per continent, with the same questions and answer options for everyone. It changes at midnight UTC. You get one attempt; score ranks first and time breaks ties. It tracks a daily streak and gives a Wordle-style result to share
- **Passport:** the first time you name a country's capital correctly, it gets a stamp. The passport view shows all 194 countries by region
- **Friends board:** everyone's passport ranked by stamps (ties go to flights boarded) or by today's Daily Flight, with today's result, daily streak, accuracy, km flown and best streak
- **Selfie postcards:** once you have a city's stamp, you can make a postcard from it. Take a selfie or choose a photo, drag and zoom it into the polaroid, pick day, sunset or night, and save it as a PNG. Each capital gets a skyline drawn from its name, with building styles that depend on the region. The photo never leaves the device
- **Fun facts:** 388 short facts, two per country: one about the capital and one about the country. One appears after every answer
- **Layover and review:** the trip summary lists the flights you missed, with their facts, and offers an instant retry. Missed capitals come back in later trips (up to 40% of a trip) until you answer them correctly twice
- Best score per route is saved in the browser

## Competing with friends

The shared version runs as a claude.ai artifact, which stores each player's passport in the artifact's database. Each player can write only their own passport. Opened as a plain file, the game keeps your passport in this browser only.

Keys: `1`–`4` to answer, `Enter` for the next flight.
