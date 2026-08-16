# Research & References

## Primary references

1. **Utilizing Mobile Application Technologies for Enhanced Sustainable Waste Management in Urban India**
   ResearchGate — [Publication 383636510](https://www.researchgate.net/publication/383636510_Utilizing_Mobile_Application_Technologies_for_Enhanced_Sustainable_Waste_Management_in_Urban_India)

   Examines how mobile platforms can improve waste collection and citizen participation in
   Indian urban contexts. Directly supports the app-based reporting model at the centre of
   Bin Buddy.

2. **Application of Machine Learning Algorithms in Municipal Solid Waste Management: A Mini Review**
   ResearchGate — [Publication 353297933](https://www.researchgate.net/publication/353297933_Application_of_machine_learning_algorithms_in_municipal_solid_waste_management_A_mini_review)

   Reviews ML techniques applied to municipal solid waste — classification, generation
   forecasting and route optimisation. Underpins the TensorFlow Lite classifier and the
   hotspot-mapping approach.

## Regulatory context

- **E-Waste (Management) Rules, India** — governs collection, storage and processing of
  electronic waste. Bin Buddy routes all e-waste through CPCB-certified recyclers rather than
  taking custody of it.
- **Solid Waste Management Rules, India** — mandates source segregation and defines municipal
  obligations. Bin Buddy's segregation categories align with this framework.
- **Swachh Bharat Mission (Urban)** — the funding and policy environment that makes municipal
  partnership and grant revenue realistic.

## Comparable platforms

| Platform | Model | How Bin Buddy differs |
|---|---|---|
| **Recykal** | B2B digital marketplace connecting waste generators to recyclers | Bin Buddy is citizen-first and includes reporting of uncollected waste, not just transactions |
| **Scrap Uncle** | On-demand scrap pickup from households | Bin Buddy adds ML classification, hotspot analytics and a rewards layer, and surfaces waste nobody booked |

## Datasets for the ML component

- **TrashNet** — labelled images across glass, paper, cardboard, plastic, metal and trash;
  a viable starting point for the classifier before pilot data accumulates.
- **Pilot-collected data** — user-submitted reports, corrected at the sorting facility, become
  the fine-tuning set that adapts the model to Indian urban waste specifically.
