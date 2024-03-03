
# Battery Industry

## Introduction

First of all, this is a high-competition and high investment return (ROI) industry, with direct impact on many
high influential use-cases such as EV, New Energy, Clean Energy to even National Security issues. We might need 
strategies to deal with a huge market with heterogeous landscape of market players to start with. 
A Niche Market strategy can also benefit if we focus on a small component of this huge "elephant".


## Pain-points

### Too many subtleties of parameters during the whole battery modeling process

- What exact metal materials to use?
  - NMC, Lithium nickel manganese cobalt oxides, LiNi_xMn_yCo_(1-x-y)O_2
  - LFP, lithium ferro-phosphate, LiFePO_4
  - LCO, Lithium cobalt oxide, LiCoO_2
  - so on and so forth


- There is a lot "Meta-data" in addition to material structure data
  - What temperature was used in heating process?
  - What pressure, humidity were used?
  - What was the pressure distribution?
  - What was the mechanical connections of the particles?
  - What was the exact lamination process?
  - What was the achieved Energy Density


- Too many confounders in the process, which makes computational battery modeling, software business in general
more difficult to be adopted in this industry (conventional industry, not too many people talk about "cloud"
it seems)


- There are existing model-based approach / software in this industry, it's a bit more than just material itself,
but more dedicated for battery as a comprehensive system:
  - ComSOL
    - https://www.comsol.com/
    - Battery material modeling, physics-based or model-based
    - Simulations
    - 3-4 K USD per license per user
    - 100 M USD level of ARR, well established, "conventional" software provider, founded 1980's
  - VOLAIQ
    - https://www.voltaiq.com/
    - Battery optimization, modeling, analytics software
    - Startup, raised 12 M USD as is, valuation at 50 M USD
    - Revenue estimated to be 4 M USD ARR (with 40-50 people)
    

- New opportunities for data-driven approach (ML, GenAI)
  - Most likely, we'll have to pick up our own battle in this whole chain of processes, as discussed above there 
  are so many factors, uncertainties, parameters, or in our case, data to collect such that Gen AI can
  actually learn from data, therefore make inferences on proposals for new materials, material optimizations
  
  - If we only focus on material itself, the "cons" of this strategy would be: we are not solving the problem,
  but only solved part of the problem, it's not a total solution, which can limit the use cases in this industry

  - For the use case of San Francisco State University example: a good question to ask is whether researches can
  can take what AI generated, and use it end-to-end within one software to develop a new battery cell. Do they still
  need other tools such as ComSOL, VOLAQ, etc. to finish the whole process?


### Dis-connect between Cell Cycling Data and Lab Test Data / Meta-data

This appears to be logistics wise problem or pain-point in battery industry which could generate a "Niche Market"
use case. There are no software that combines both lab test data (manually entered data) such as pressure,
temperature, humidity, so on and so forth, and then connect or link that data to the battery cell cycling test
data.

It appears to me these are two difference spaces, some software that can make this data aggregation, or management
could be a good business. But that might fall out of the scope of this case study.


## Challenges

### Data Sharing would be challenging

A med-size startup company spent 17 M USD or so to run experimentation, testings and collect those battery cell
cycle data, lab test data, it would be the last thing to do for them to share any of those data with another 
company, or SAAS service provider even (data security, cybersecurity requirement can be high).

This is very similar in my past experience in Self-driving Car industry, all the "big boy" players spend tons 
of money to collect those road testing, camera, LIDAR, RADAR data, they are not going to share data among 
different companies... it has been almost a decade, i don't see any companies sharing data yet even though
I see many people are working towards sharing road testing data such as the whole industry can move together
to next phase to build a safer and better autonomous car. Very good idea, but it is what it is in terms of
conflict of interest, especially when we talk about a huge market of 100 B USD business of robot-taxi service.

Without the testing data, it would be hard for Gen AI to pick up or learn so-called "embedding vectors" or
mathematical representation of materials, other parameters (temperature, pressure etc.) thus provide an
end-to-end total solution. Gen AI might be able to provide part of the whole process such as material structure
but the limitation is already discussed in Pain-point session. 


## Business Model

Assuming we use a SAAS model to start with, most likely we start with big battery companies such as Panasonic, 
LG, and they probably won't share their data with other companies as discussed above. The SAAS software can only train
on their own proprietary data, and provide services on generating new materials, save cost, improve efficiency,
cut down go-to-market timeline, so on and so forth.

### Big Battery Supplier

#### Panasonic (Panasonic Energy)

Panasonic's main US customer is Tesla. They provide 10% of the EV batteries globally. They make 785 M USD profit!
Their annual revenue is about 5 B USD as of 2023 and they claim to target for 17.9 B USD revenue by 2031

https://asia.nikkei.com/Business/Automobiles/Tesla-partner-Panasonic-weighs-supplying-EV-batteries-to-Subaru#:~:text=In%20June%2C%20battery%20unit%20Panasonic,the%20year%20ended%20March%202023.

The margin is about 16% for them, not a lot though, below 20% are generally considered "something that can be
improved"

However, on the other hand, there isn't so many of such big battery players, maybe 10 to 20 only, selling to just
10-20 companies is difficult, you need dive into the med-size to small startup companies that are working on
solid state batteries, or any type of material battery technologies.

### Startup Companies on Battery Technology


#### Sila (Raised 930 M USD)

Focus: nanostructured materials

Panasonic announced an agreement to buy nano-composite silicon anode material from Sila Nanotechnologies Inc.

- 12 years testing, 80,000 iterations
- 395 M USD ARR, estimated and projection for 2024



#### Blue Current (Raised 40+ M USD)

Focus: combines polymers and ceramics to enable silicon

- Estimated revenue: 7 M USD (40-50 FTE)


### Alternative Strategies

An alternative thought would be rather than a "business model", we call it "exit strategy", if a technology
can train on those battery cell cycling data, lab data, structure data and can propose new materials based
upon user's input or prompting context, that technology itself could probably be easily adopted, acquired
by one these "deep-pocket" battery companies such as Panasonic. It's another story-telling then in this case.

