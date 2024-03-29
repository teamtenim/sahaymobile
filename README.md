![image](https://user-images.githubusercontent.com/49993666/118434387-9bfc1400-b6fa-11eb-90c5-6bf2d5039001.png)

> A product to help humanity, and India as a country, especially during the novel COVID-19 stricken times, by consolidating the health care system and all different medical faculties onto one platform.

### View the deployed site at [sahay.us](https://sahay.us)
### Web app/Dashboard at [app.sahay.us](https://app.sahay.us)
### Download the mobile app [here](https://sahay.us/download)
### View our branding [here](https://sahay.us/design)

## Source Code

- [Mobile App](https://github.com/Team-TENIM/sahaymobile)
- [API/Web Application](https://github.com/Team-TENIM/sahaydashboard)
- [Promotional Website](https://github.com/Team-TENIM/teamtenim)

## Steps to run

- Install dependencies
- Make sure you have the Ionic CLI installed
- Run `ionic start` on the terminal and the app should be live on your local host browser.
- Use the inspect element panel and resize it according to a mobile device's dimensions.

<br />

![image](https://user-images.githubusercontent.com/49993666/118526062-cd5ceb80-b6ca-11eb-90a8-651de9a3ab34.png)

<br />

The app essentially allows hospitals to collaborate and share resources using a simple User Interface. When a hospital is in need of essential equipment urgently, and another hospital is willing to help out, they can contact each other and set up a delivery right through the app.

We provide hospitals with a platform to display all of their resources (like their medical supplies and equipment) and their staff, to keep them in check. It also gives you information about all other hospitals and their capacities, in a certain radius. Using this information, hospitals can place requests - and their level of urgency - for any commodities or capacity. Thus working together, and pitching in their resources, all our medical faculties will be able to manage the huge influx of patients and lack of equipment without too much worry. **These resources once shared, the transfer of supplies is validated with the use of blockchain technology.**

The dashboard system allows hospital's to manage their own resources, equipment, and staff in an efficient way. It can be accessed through any device (laptops, mobiles, tablets - whatever’s most convenient), anywhere in the world. Our API is updated in real-time which allows for an efficient workflow and better overall management experience.

## Features

![image](https://user-images.githubusercontent.com/49993666/118434487-cd74df80-b6fa-11eb-97ed-ec50526489a1.png)


## How we built it

Prototype was built on Figma, along with branding. The app was built using VueJS and Ionic. We used a NodeJS API to interact with it. The promotional website was built using Vue 3. Backend functionality was implemented using Google Cloud Platform and Python. The Web App was built with express and rendered using the pug templating engine. We built these separate apps so that it's easier for hospital staff to use any device available and manage the hospital quickly and efficiently with a seamless user experience.

## Database

We deployed MongoDB as a fast access datastore for storing requested materials, supplies and equipment as part of our request, and for real time invetory management and tracking. The datastore stores quantities, types and units of various medical essentials such as blood, plasma, medicines, essential equipment and gear. The realtime data is indexed using a composite key made up of a hospital location markerid, a timestamp and a type indicator. The inventory of these critical supplies are tracked real time, therefore allowing less chances of mismatches or supply underruns occurring during emergencies.

## User Flow

After spending a lot of time deliberating, researching and perfecting our UI prototypes, and the final look on the app, we came up with a design which not only combated the problems our competitors face - like that of having a learning curve to operate the service, we made it easy to locate all resources and manage everything that needed to be looked at, through the home page itself. Our belief was to make a very intuitive platform, and one that would streamline the process of management greatly.

<br />

![image](https://user-images.githubusercontent.com/49993666/118434665-1036b780-b6fb-11eb-84d6-2fdb073a00c8.png)

<br />

## Web Application

![PPT](https://user-images.githubusercontent.com/49993666/118533775-67289680-b6d3-11eb-96c6-7d59427fcefa.png)

The dashboard system, where hospitals manage their own staff, equipment and supplies, and keep it in check, allows hospitals to share their resources and come together. The transfer of goods is verified using blockchain.

During this almost Third World War, all medical faculties would have to work together, pitch in, look beyond just profit to help out other surrounding hospitals to keep operating, and ensure that no patient is left unseen.

Let's work together to defeat the virus.

## System Architecture

![system architecture](https://user-images.githubusercontent.com/49993666/118532419-e7e69300-b6d1-11eb-92a5-c2e04ef4cdc4.png)

## What's next for Sahay

So we aim to provide a service to assist the medical industry in any way, and not binding with financial constraints. We would start off with a low scale release and testing phase, with around 100 - 200 users. Over the next month or two, start with funding to get it into a stable state and later release it into Delhi with a marketing campaign. If things go well, over the next 1-2 months we expand on our hospital database and provide our SaaS to even more hospitals. Later we plan for a nation-wide launch, get some sort of approval and help from the government to allow our team to expand. Sahay is not only limited to India and can also spread internationally, as it is essentially an application and wouldn't require too much effort to push ahead.

As we grow, we also have plans to release a public API as we'll have a large database of equipment that hospitals have. This data could be used by other developers to build apps that improve the interaction between users and hospitals. 

For example, in the current scenario in India, where everyone is looking for beds, remedesivir, and other resources, people are having to manually call up hospitals and suppliers to verify whether these resources are available. As our API updates in real-time, this verfification step can be removed and people in need can directly check which reources are available.

## Challenges we ran into

Storing images onto Blockchain, was something we discovered to be the way harder than it looks like and was seemingly impossible to figure out within a few hours. We hence decided to opt working with strings. The way to do it is store it off the chain, unless you use IPFS.

## Accomplishments that we're proud of

Heavily researching the only thing close to our idea - hospital management programs - we built a service that not only has clean, minimalistic UI/UX, but also does not require any training to use, thus saving Hospitals and our users' money and hours to train a person. The fact that we could code in an almost replica of our design prototype into the final product was an impressive achievement for us. We also explored and delved into many new technologies, simultaneously learning and implementing blockchain technology into our product within less than 36 hours.

## What we learned

We learned more about the what and why to the problems of resource shortage in our country, and realised the stark difference in statements from nearby hospitals, with some pleading for certain resources and some within a few kilometres of radius saying they had excess resources. Yet there seemed to be no solution to these problems, and that led to the existence of our project. We learned more as to how blockchain technology can be used to verified items across the globe through something as simple as ID codes, which can validate the source of the supplies _(tackling the major problems like the black-market of essential life saving medicines and drugs, and the dilution and fake products in the market.)_

## The team

- Arhaan Bahadur
- Siddhayak Goyal
