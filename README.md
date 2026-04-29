# Canada Net-Zero Spending Accountability Agent

An AI-powered accountability tool that queries 1.27M federal grants and contributions records (2006–2025) to evaluate whether Canada's spending aligns with its legal obligations under the Canadian  Net-Zero Emissions Accountability Act (2021).

Canada Net-Zero Spending Accountability Agent: https://www.stackai.com/chat/69f2296d4d67063ef2569ec9-3U22uBuvmOoCDs55QLuvlo

Sample output: https://www.stackai.com/chat/69f2296d4d67063ef2569ec9-3U22uBuvmOoCDs55QLuvlo/share/69d4a905-8871-4869-b3dc-cb94e691b051?title=Canada%27s+federal+spending+and+Net-Zero+targets&date=2026-04-29T17%3A45%3A51.429Z

Video: https://www.loom.com/share/7c7d964c1fe14d309634a6454da08d36

Description: Canada's Net-Zero Spending Accountability Agent is an AI-powered analyst that queries 1.27 million federal grants and contributions records (2006–2025) to evaluate whether Canada's actual spending aligns with its legal obligations under the Canadian Net-Zero Emissions Accountability Act (2021). The agent classifies federal spending as emissions-reducing or emissions-increasing, identifies the projects and recipients most aligned and misaligned with Canada's 2030 NDC targets, and delivers a plain-language verdict grounded in real dollar amounts from the data. Built on StackAI with a live PostgreSQL connection to the hackathon database, it makes climate accountability queryable by anyone.

<img width="969" height="593" alt="Screenshot 2026-04-29 at 2 40 34 PM" src="https://github.com/user-attachments/assets/cd298069-77b5-4483-8c63-65ea0deab05d" />
<img width="966" height="587" alt="Screenshot 2026-04-29 at 2 41 04 PM" src="https://github.com/user-attachments/assets/0bd23680-c20b-4dae-a880-423388ea84d5" />
<img width="969" height="586" alt="Screenshot 2026-04-29 at 2 41 42 PM" src="https://github.com/user-attachments/assets/cc229d9e-31d4-4c23-a8e9-066f1a1a3335" />
<img width="967" height="591" alt="Screenshot 2026-04-29 at 2 41 22 PM" src="https://github.com/user-attachments/assets/b922923d-7860-4f9b-9c06-67ac5c760ffd" />
<img width="977" height="590" alt="Screenshot 2026-04-29 at 2 41 58 PM" src="https://github.com/user-attachments/assets/b22cd01d-aadf-425b-97d9-a0fbc37e5ae6" />
<img width="963" height="494" alt="Screenshot 2026-04-29 at 2 42 14 PM" src="https://github.com/user-attachments/assets/391d9cc3-3a33-45d4-98e4-d77c9fd1d7b3" />
<img width="707" height="363" alt="Screenshot 2026-04-29 at 2 44 11 PM" src="https://github.com/user-attachments/assets/e8d0978d-c189-4956-9cfe-230bc47dc2d4" />
<img width="966" height="590" alt="Screenshot 2026-04-29 at 2 42 55 PM" src="https://github.com/user-attachments/assets/b7fdc163-fe3a-4260-b824-b55748f1772d" />

## What it does
- Classifies federal spending as emissions-reducing or emissions-increasing using keyword analysis across 51 departments
- Identifies departments and recipients most aligned and misaligned with Canada's 2030 NDC targets (36–44% reduction below 2005 levels)
- Delivers a plain-language verdict — ALIGNED / PARTIALLY ALIGNED / MISALIGNED — grounded in real dollar amounts from the data
- Flags high-value contradictions (e.g. $200M Cedar LNG grant in 2025 while Canada's climate action is rated Highly Insufficient by Climate Action Tracker)

## Data source
Federal Grants & Contributions — Government of Canada Open Data Portal  
1,275,521 records · 51 departments · 2006–2025  
Via the GovAlta/agency-26-hackathon PostgreSQL database: https://github.com/GovAlta/agency-26-hackathon/tree/main

## Policy framework
- Canadian Net-Zero Emissions Accountability Act (S.C. 2021, c. 22) https://laws-lois.justice.gc.ca/eng/acts/c-19.3/fulltext.html
- Canada's Nationally Defined Contributions (NDCs) - 2030 NDC: 36–44% reduction below 2005 levels; 2035 NDC: 40–49% reduction below 2005 levels https://unfccc.int/sites/default/files/2025-02/Canada%27s%202035%20Nationally%20Determined%20Contribution_ENc.pdf
- Climate Action Tracker assessment (Oct 2025): Canada's climate action is Highly Insufficient https://climateactiontracker.org/countries/canada/2035-ndc/

## Built with
- StackAI — agent framework and PostgreSQL tool
- Anthropic Claude — reasoning and SQL generation

## Built at
​Agency 2026 Ottawa - National Hackathon 
April 29, 2026

## Disclaimer
This is a prototype and AI can make mistakes. 

## Video and Images from Previous Iteration
https://www.loom.com/share/0c5e2328f8a4473d981fdafdc8a90be2
<img width="1041" height="542" alt="Screenshot 2026-04-29 at 2 35 23 PM" src="https://github.com/user-attachments/assets/e2ae0835-a026-484b-b1ab-a1e68a9855b9" />

