# 🗺 PostgreSQL Flag Quiz Website   <img height="80px" align="center" src="https://github.com/shanibider/Nodejs-PostgreSQL-Secrets-Sharing/assets/72359805/19796f0e-199f-4ac4-a4e6-d68ea90dd354"> 

### Check out the website [here](https://postgresql-flag-quiz.onrender.com/)!   

This is a web application that serves as a quiz game for identifying flags stored in a PostgreSQL database. Built with -
### Node.js, Express, JavaScript, and EJS (Embedded JavaScript) <img height=20px src="https://skillicons.dev/icons?i=postgresql"> <img height=20px src="https://skillicons.dev/icons?i=express"> <img height=20px src="https://skillicons.dev/icons?i=nodejs"> <img height=20px src="https://skillicons.dev/icons?i=js">


<div align="center">
<img height="250px" src="https://github.com/shanibider/PostgreSQL-Flag-Quiz-Website/assets/72359805/5fd2dc1a-4e2c-424c-9b19-c1caf0bb00f9"></div>

> [!NOTE]
> Windows does not display flag images for emoji. Instead, Windows will show you the country code which looks this: "🇦🇫" :
> <img height=250px src="https://github.com/shanibider/The-Complete-2024-Web-Development-Bootcamp/assets/72359805/bb6c3ccd-573c-4ee2-8a79-442dcb9e0b18">
>
> <img height=30px src="https://github.com/shanibider/The-Complete-2024-Web-Development-Bootcamp/assets/72359805/7686a8b1-fafa-40a1-9574-acdea39aea90"> So as a Windows user, the easiest way to see the flags is simply to use the Mozilla Firefox browser (instead of Chrome).
> Firefox displays flags just fine!


## Table of Contents
- [ ] [Tech Stack](#tech-stack)
- [ ] [Features](#features)
- [ ] [Dependencies](#dependencies)
- [ ] [Getting Started](#getting-started)
- [ ] [Database Schema](#database-schema)
- [ ] [Usage](#usage)
- [ ] [Flags](#flags)
- [ ] [Cheat Sheet for Country Emojis](#cheat-sheet-for-country-emojis)
- [ ] [License](#license)

## Tech stack💻
[![My Skills](https://skillicons.dev/icons?i=nodejs,express,js,bootstrap,html,css)](https://skillicons.dev)

- [x] **Node.js:** JavaScript runtime environment for executing JavaScript code server-side.
- [x] **Express.js:** A web application framework for Node.js used for building web applications and APIs.
- [x] **EJS (Embedded JavaScript):** Templating engine for generating HTML markup with plain JavaScript.
- [x] **PostgreSQL:** Open-source relational database system for storing flag data.
- [x] **Body-parser:** Middleware for parsing incoming request bodies in Express.
- [x] **pg (node-postgres):** A PostgreSQL client for Node.js used to interact with the PostgreSQL database.
- [x] **dotenv:** A zero-dependency module that loads environment variables from a `.env` file into `process.env`.


## Features🚀

- [ ] Users can play a quiz game where they are presented with random flags and must input the corresponding country name.
- [ ] The application keeps track of the total score, displaying it to the user after each guess.
- [ ] Utilizes PostgreSQL as the database backend to store flag data.

## Screenshots🖼️
![22](https://github.com/shanibider/PostgreSQL-Flag-Quiz-Website/assets/72359805/b49e1699-26ac-4f26-a5ed-3ebcdec83e72)


## Dependencies🧱

- Express.js: A web application framework for Node.js used for building web applications and APIs.
- Body-parser: Middleware for parsing incoming request bodies in Express.
- pg (node-postgres): A PostgreSQL client for Node.js used to interact with the PostgreSQL database.
- dotenv: A zero-dependency module that loads environment variables from a `.env` file into `process.env`.


## Getting Started🎯

1. Clone this repository to your local machine.
2. Install dependencies using `npm install`.
3. Set up a PostgreSQL database and populate it with flag data.
4. Create a `.env` file in the root directory and add your database credentials:

   ```plaintext
   DB_USER=your_username
   DB_HOST=your_host
   DB_DATABASE=your_database
   DB_PASSWORD=your_password
   DB_PORT=your_port

5. Run the application using npm start.
6. Access the application in your web browser at http://localhost:3000 .
 
 
 ## Database Schema<img height=30px src="https://skillicons.dev/icons?i=postgresql"> 
The database should contain a table named flags with columns representing flag data, such as name, image_url, etc.


## Usage📝
- [ ] Visit the homepage (/) to start the quiz game.
- [ ] Input the corresponding country name for the presented flag and submit your answer.
- [ ] The application will indicate whether your answer is correct and display the total score.
- [ ] Continue playing to test your knowledge of flags!


## flags📔

![emoji_flags](https://github.com/shanibider/Readme-tests/assets/72359805/b0e8ec35-18db-4f4d-a5a6-250b8a05e346)


### Cheat Sheet for Country Emojis📔 

| | ico | shortcode | ico | shortcode | |
| - | :-: | - | :-: | - | - |
| [top](#flags) | :ascension_island: | `:ascension_island:` | :andorra: | `:andorra:` | [top](#table-of-contents) |
| [top](#flags) | :united_arab_emirates: | `:united_arab_emirates:` | :afghanistan: | `:afghanistan:` | [top](#table-of-contents) |
| [top](#flags) | :antigua_barbuda: | `:antigua_barbuda:` | :anguilla: | `:anguilla:` | [top](#table-of-contents) |
| [top](#flags) | :albania: | `:albania:` | :armenia: | `:armenia:` | [top](#table-of-contents) |
| [top](#flags) | :angola: | `:angola:` | :antarctica: | `:antarctica:` | [top](#table-of-contents) |
| [top](#flags) | :argentina: | `:argentina:` | :american_samoa: | `:american_samoa:` | [top](#table-of-contents) |
| [top](#flags) | :austria: | `:austria:` | :australia: | `:australia:` | [top](#table-of-contents) |
| [top](#flags) | :aruba: | `:aruba:` | :aland_islands: | `:aland_islands:` | [top](#table-of-contents) |
| [top](#flags) | :azerbaijan: | `:azerbaijan:` | :bosnia_herzegovina: | `:bosnia_herzegovina:` | [top](#table-of-contents) |
| [top](#flags) | :barbados: | `:barbados:` | :bangladesh: | `:bangladesh:` | [top](#table-of-contents) |
| [top](#flags) | :belgium: | `:belgium:` | :burkina_faso: | `:burkina_faso:` | [top](#table-of-contents) |
| [top](#flags) | :bulgaria: | `:bulgaria:` | :bahrain: | `:bahrain:` | [top](#table-of-contents) |
| [top](#flags) | :burundi: | `:burundi:` | :benin: | `:benin:` | [top](#table-of-contents) |
| [top](#flags) | :st_barthelemy: | `:st_barthelemy:` | :bermuda: | `:bermuda:` | [top](#table-of-contents) |
| [top](#flags) | :brunei: | `:brunei:` | :bolivia: | `:bolivia:` | [top](#table-of-contents) |
| [top](#flags) | :caribbean_netherlands: | `:caribbean_netherlands:` | :brazil: | `:brazil:` | [top](#table-of-contents) |
| [top](#flags) | :bahamas: | `:bahamas:` | :bhutan: | `:bhutan:` | [top](#table-of-contents) |
| [top](#flags) | :bouvet_island: | `:bouvet_island:` | :botswana: | `:botswana:` | [top](#table-of-contents) |
| [top](#flags) | :belarus: | `:belarus:` | :belize: | `:belize:` | [top](#table-of-contents) |
| [top](#flags) | :canada: | `:canada:` | :cocos_islands: | `:cocos_islands:` | [top](#table-of-contents) |
| [top](#flags) | :congo_kinshasa: | `:congo_kinshasa:` | :central_african_republic: | `:central_african_republic:` | [top](#table-of-contents) |
| [top](#flags) | :congo_brazzaville: | `:congo_brazzaville:` | :switzerland: | `:switzerland:` | [top](#table-of-contents) |
| [top](#flags) | :cote_divoire: | `:cote_divoire:` | :cook_islands: | `:cook_islands:` | [top](#table-of-contents) |
| [top](#flags) | :chile: | `:chile:` | :cameroon: | `:cameroon:` | [top](#table-of-contents) |
| [top](#flags) | :cn: | `:cn:` | :colombia: | `:colombia:` | [top](#table-of-contents) |
| [top](#flags) | :clipperton_island: | `:clipperton_island:` | :costa_rica: | `:costa_rica:` | [top](#table-of-contents) |
| [top](#flags) | :cuba: | `:cuba:` | :cape_verde: | `:cape_verde:` | [top](#table-of-contents) |
| [top](#flags) | :curacao: | `:curacao:` | :christmas_island: | `:christmas_island:` | [top](#table-of-contents) |
| [top](#flags) | :cyprus: | `:cyprus:` | :czech_republic: | `:czech_republic:` | [top](#table-of-contents) |
| [top](#flags) | :de: | `:de:` | :diego_garcia: | `:diego_garcia:` | [top](#table-of-contents) |
| [top](#flags) | :djibouti: | `:djibouti:` | :denmark: | `:denmark:` | [top](#table-of-contents) |
| [top](#flags) | :dominica: | `:dominica:` | :dominican_republic: | `:dominican_republic:` | [top](#table-of-contents) |
| [top](#flags) | :algeria: | `:algeria:` | :ceuta_melilla: | `:ceuta_melilla:` | [top](#table-of-contents) |
| [top](#flags) | :ecuador: | `:ecuador:` | :estonia: | `:estonia:` | [top](#table-of-contents) |
| [top](#flags) | :egypt: | `:egypt:` | :western_sahara: | `:western_sahara:` | [top](#table-of-contents) |
| [top](#flags) | :eritrea: | `:eritrea:` | :es: | `:es:` | [top](#table-of-contents) |
| [top](#flags) | :ethiopia: | `:ethiopia:` | :eu: | `:eu:` <br /> `:european_union:` | [top](#table-of-contents) |
| [top](#flags) | :finland: | `:finland:` | :fiji: | `:fiji:` | [top](#table-of-contents) |
| [top](#flags) | :falkland_islands: | `:falkland_islands:` | :micronesia: | `:micronesia:` | [top](#table-of-contents) |
| [top](#flags) | :faroe_islands: | `:faroe_islands:` | :fr: | `:fr:` | [top](#table-of-contents) |
| [top](#flags) | :gabon: | `:gabon:` | :gb: | `:gb:` <br /> `:uk:` | [top](#table-of-contents) |
| [top](#flags) | :grenada: | `:grenada:` | :georgia: | `:georgia:` | [top](#table-of-contents) |
| [top](#flags) | :french_guiana: | `:french_guiana:` | :guernsey: | `:guernsey:` | [top](#table-of-contents) |
| [top](#flags) | :ghana: | `:ghana:` | :gibraltar: | `:gibraltar:` | [top](#table-of-contents) |
| [top](#flags) | :greenland: | `:greenland:` | :gambia: | `:gambia:` | [top](#table-of-contents) |
| [top](#flags) | :guinea: | `:guinea:` | :guadeloupe: | `:guadeloupe:` | [top](#table-of-contents) |
| [top](#flags) | :equatorial_guinea: | `:equatorial_guinea:` | :greece: | `:greece:` | [top](#table-of-contents) |
| [top](#flags) | :south_georgia_south_sandwich_islands: | `:south_georgia_south_sandwich_islands:` | :guatemala: | `:guatemala:` | [top](#table-of-contents) |
| [top](#flags) | :guam: | `:guam:` | :guinea_bissau: | `:guinea_bissau:` | [top](#table-of-contents) |
| [top](#flags) | :guyana: | `:guyana:` | :hong_kong: | `:hong_kong:` | [top](#table-of-contents) |
| [top](#flags) | :heard_mcdonald_islands: | `:heard_mcdonald_islands:` | :honduras: | `:honduras:` | [top](#table-of-contents) |
| [top](#flags) | :croatia: | `:croatia:` | :haiti: | `:haiti:` | [top](#table-of-contents) |
| [top](#flags) | :hungary: | `:hungary:` | :canary_islands: | `:canary_islands:` | [top](#table-of-contents) |
| [top](#flags) | :indonesia: | `:indonesia:` | :ireland: | `:ireland:` | [top](#table-of-contents) |
| [top](#flags) | :israel: | `:israel:` | :isle_of_man: | `:isle_of_man:` | [top](#table-of-contents) |
| [top](#flags) | :india: | `:india:` | :british_indian_ocean_territory: | `:british_indian_ocean_territory:` | [top](#table-of-contents) |
| [top](#flags) | :iraq: | `:iraq:` | :iran: | `:iran:` | [top](#table-of-contents) |
| [top](#flags) | :iceland: | `:iceland:` | :it: | `:it:` | [top](#table-of-contents) |
| [top](#flags) | :jersey: | `:jersey:` | :jamaica: | `:jamaica:` | [top](#table-of-contents) |
| [top](#flags) | :jordan: | `:jordan:` | :jp: | `:jp:` | [top](#table-of-contents) |
| [top](#flags) | :kenya: | `:kenya:` | :kyrgyzstan: | `:kyrgyzstan:` | [top](#table-of-contents) |
| [top](#flags) | :cambodia: | `:cambodia:` | :kiribati: | `:kiribati:` | [top](#table-of-contents) |
| [top](#flags) | :comoros: | `:comoros:` | :st_kitts_nevis: | `:st_kitts_nevis:` | [top](#table-of-contents) |
| [top](#flags) | :north_korea: | `:north_korea:` | :kr: | `:kr:` | [top](#table-of-contents) |
| [top](#flags) | :kuwait: | `:kuwait:` | :cayman_islands: | `:cayman_islands:` | [top](#table-of-contents) |
| [top](#flags) | :kazakhstan: | `:kazakhstan:` | :laos: | `:laos:` | [top](#table-of-contents) |
| [top](#flags) | :lebanon: | `:lebanon:` | :st_lucia: | `:st_lucia:` | [top](#table-of-contents) |
| [top](#flags) | :liechtenstein: | `:liechtenstein:` | :sri_lanka: | `:sri_lanka:` | [top](#table-of-contents) |
| [top](#flags) | :liberia: | `:liberia:` | :lesotho: | `:lesotho:` | [top](#table-of-contents) |
| [top](#flags) | :lithuania: | `:lithuania:` | :luxembourg: | `:luxembourg:` | [top](#table-of-contents) |
| [top](#flags) | :latvia: | `:latvia:` | :libya: | `:libya:` | [top](#table-of-contents) |
| [top](#flags) | :morocco: | `:morocco:` | :monaco: | `:monaco:` | [top](#table-of-contents) |
| [top](#flags) | :moldova: | `:moldova:` | :montenegro: | `:montenegro:` | [top](#table-of-contents) |
| [top](#flags) | :st_martin: | `:st_martin:` | :madagascar: | `:madagascar:` | [top](#table-of-contents) |
| [top](#flags) | :marshall_islands: | `:marshall_islands:` | :macedonia: | `:macedonia:` | [top](#table-of-contents) |
| [top](#flags) | :mali: | `:mali:` | :myanmar: | `:myanmar:` | [top](#table-of-contents) |
| [top](#flags) | :mongolia: | `:mongolia:` | :macau: | `:macau:` | [top](#table-of-contents) |
| [top](#flags) | :northern_mariana_islands: | `:northern_mariana_islands:` | :martinique: | `:martinique:` | [top](#table-of-contents) |
| [top](#flags) | :mauritania: | `:mauritania:` | :montserrat: | `:montserrat:` | [top](#table-of-contents) |
| [top](#flags) | :malta: | `:malta:` | :mauritius: | `:mauritius:` | [top](#table-of-contents) |
| [top](#flags) | :maldives: | `:maldives:` | :malawi: | `:malawi:` | [top](#table-of-contents) |
| [top](#flags) | :mexico: | `:mexico:` | :malaysia: | `:malaysia:` | [top](#table-of-contents) |
| [top](#flags) | :mozambique: | `:mozambique:` | :namibia: | `:namibia:` | [top](#table-of-contents) |
| [top](#flags) | :new_caledonia: | `:new_caledonia:` | :niger: | `:niger:` | [top](#table-of-contents) |
| [top](#flags) | :norfolk_island: | `:norfolk_island:` | :nigeria: | `:nigeria:` | [top](#table-of-contents) |
| [top](#flags) | :nicaragua: | `:nicaragua:` | :netherlands: | `:netherlands:` | [top](#table-of-contents) |
| [top](#flags) | :norway: | `:norway:` | :nepal: | `:nepal:` | [top](#table-of-contents) |
| [top](#flags) | :nauru: | `:nauru:` | :niue: | `:niue:` | [top](#table-of-contents) |
| [top](#flags) | :new_zealand: | `:new_zealand:` | :oman: | `:oman:` | [top](#table-of-contents) |
| [top](#flags) | :panama: | `:panama:` | :peru: | `:peru:` | [top](#table-of-contents) |
| [top](#flags) | :french_polynesia: | `:french_polynesia:` | :papua_new_guinea: | `:papua_new_guinea:` | [top](#table-of-contents) |
| [top](#flags) | :philippines: | `:philippines:` | :pakistan: | `:pakistan:` | [top](#table-of-contents) |
| [top](#flags) | :poland: | `:poland:` | :st_pierre_miquelon: | `:st_pierre_miquelon:` | [top](#table-of-contents) |
| [top](#flags) | :pitcairn_islands: | `:pitcairn_islands:` | :puerto_rico: | `:puerto_rico:` | [top](#table-of-contents) |
| [top](#flags) | :palestinian_territories: | `:palestinian_territories:` | :portugal: | `:portugal:` | [top](#table-of-contents) |
| [top](#flags) | :palau: | `:palau:` | :paraguay: | `:paraguay:` | [top](#table-of-contents) |
| [top](#flags) | :qatar: | `:qatar:` | :reunion: | `:reunion:` | [top](#table-of-contents) |
| [top](#flags) | :romania: | `:romania:` | :serbia: | `:serbia:` | [top](#table-of-contents) |
| [top](#flags) | :ru: | `:ru:` | :rwanda: | `:rwanda:` | [top](#table-of-contents) |
| [top](#flags) | :saudi_arabia: | `:saudi_arabia:` | :solomon_islands: | `:solomon_islands:` | [top](#table-of-contents) |
| [top](#flags) | :seychelles: | `:seychelles:` | :sudan: | `:sudan:` | [top](#table-of-contents) |
| [top](#flags) | :sweden: | `:sweden:` | :singapore: | `:singapore:` | [top](#table-of-contents) |
| [top](#flags) | :st_helena: | `:st_helena:` | :slovenia: | `:slovenia:` | [top](#table-of-contents) |
| [top](#flags) | :svalbard_jan_mayen: | `:svalbard_jan_mayen:` | :slovakia: | `:slovakia:` | [top](#table-of-contents) |
| [top](#flags) | :sierra_leone: | `:sierra_leone:` | :san_marino: | `:san_marino:` | [top](#table-of-contents) |
| [top](#flags) | :senegal: | `:senegal:` | :somalia: | `:somalia:` | [top](#table-of-contents) |
| [top](#flags) | :suriname: | `:suriname:` | :south_sudan: | `:south_sudan:` | [top](#table-of-contents) |
| [top](#flags) | :sao_tome_principe: | `:sao_tome_principe:` | :el_salvador: | `:el_salvador:` | [top](#table-of-contents) |
| [top](#flags) | :sint_maarten: | `:sint_maarten:` | :syria: | `:syria:` | [top](#table-of-contents) |
| [top](#flags) | :swaziland: | `:swaziland:` | :tristan_da_cunha: | `:tristan_da_cunha:` | [top](#table-of-contents) |
| [top](#flags) | :turks_caicos_islands: | `:turks_caicos_islands:` | :chad: | `:chad:` | [top](#table-of-contents) |
| [top](#flags) | :french_southern_territories: | `:french_southern_territories:` | :togo: | `:togo:` | [top](#table-of-contents) |
| [top](#flags) | :thailand: | `:thailand:` | :tajikistan: | `:tajikistan:` | [top](#table-of-contents) |
| [top](#flags) | :tokelau: | `:tokelau:` | :timor_leste: | `:timor_leste:` | [top](#table-of-contents) |
| [top](#flags) | :turkmenistan: | `:turkmenistan:` | :tunisia: | `:tunisia:` | [top](#table-of-contents) |
| [top](#flags) | :tonga: | `:tonga:` | :tr: | `:tr:` | [top](#table-of-contents) |
| [top](#flags) | :trinidad_tobago: | `:trinidad_tobago:` | :tuvalu: | `:tuvalu:` | [top](#table-of-contents) |
| [top](#flags) | :taiwan: | `:taiwan:` | :tanzania: | `:tanzania:` | [top](#table-of-contents) |
| [top](#flags) | :ukraine: | `:ukraine:` | :uganda: | `:uganda:` | [top](#table-of-contents) |
| [top](#flags) | :us_outlying_islands: | `:us_outlying_islands:` | :united_nations: | `:united_nations:` | [top](#table-of-contents) |
| [top](#flags) | :us: | `:us:` | :uruguay: | `:uruguay:` | [top](#table-of-contents) |
| [top](#flags) | :uzbekistan: | `:uzbekistan:` | :vatican_city: | `:vatican_city:` | [top](#table-of-contents) |
| [top](#flags) | :st_vincent_grenadines: | `:st_vincent_grenadines:` | :venezuela: | `:venezuela:` | [top](#table-of-contents) |
| [top](#flags) | :british_virgin_islands: | `:british_virgin_islands:` | :us_virgin_islands: | `:us_virgin_islands:` | [top](#table-of-contents) |
| [top](#flags) | :vietnam: | `:vietnam:` | :vanuatu: | `:vanuatu:` | [top](#table-of-contents) |
| [top](#flags) | :wallis_futuna: | `:wallis_futuna:` | :samoa: | `:samoa:` | [top](#table-of-contents) |
| [top](#flags) | :kosovo: | `:kosovo:` | :yemen: | `:yemen:` | [top](#table-of-contents) |
| [top](#flags) | :mayotte: | `:mayotte:` | :south_africa: | `:south_africa:` | [top](#table-of-contents) |
| [top](#flags) | :zambia: | `:zambia:` | :zimbabwe: | `:zimbabwe:` | [top](#table-of-contents) |









## 📫 Connect with me😊
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shani-bider/)
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://shanibider.github.io/Portfolio/)
[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shanibider@gmail.com)

<footer>
<p style="float:left; width: 20%;">
Copyright © Shani Bider, 2024
</p>
</footer>

## License📄

This project is licensed under the MIT License.
