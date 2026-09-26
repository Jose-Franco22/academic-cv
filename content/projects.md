---
title: 'Projects'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

sections:
  - block: projects-timeline
    content:
      title: Projects
      items:
        - title: StudyBuddy, a Study Group Finder
          org: Software Engineering Final Project
          date: October 2025 – December 2025
          icon: hero/code-bracket
          summary: |-
            - Built StudyBuddy with a teammate: a Flask web app where students register, log in, and create, join, and manage study groups, with group chat and file sharing, a task tracker, and video meeting links.
            - Migrated the app's database from SQLite to MongoDB Atlas with PyMongo, moving users, groups, messages, and tasks to the cloud.
            - Fixed a permissions bug that let non-creators edit groups, limiting editing and deleting to each group's creator.
            - Worked across three Agile sprints with Git and GitHub, and handled final debugging before the class presentation.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: Flask, icon: brands/flask }
            - { name: MongoDB, icon: devicon/mongodb }
            - { name: HTML, icon: devicon/html5 }
            - { name: Bootstrap, icon: devicon/bootstrap }
            - { name: Git, icon: devicon/git }
          links:
            - text: GitHub repository
              url: https://github.com/adanbarrera82/Final-Project
          figures:
            - src: uploads/projects/studybuddy-groups.png
              wide: true
              alt: StudyBuddy home page in dark mode, showing a subject filter and four study group cards with member counts, creators, members, and Join, Leave, Chat, Edit, and Delete buttons
              title: Study Group Dashboard
              caption: The home page, where students filter groups by subject and join, leave, chat in, or manage each group.

        - title: SpaceX Falcon 9 Rocket Landings
          org: IBM Data Science Professional Certificate · Applied Data Science Capstone
          date: July 2025
          summary: |-
            - Prepared and analyzed Falcon 9 launch data in Python to identify the key launch parameters that predict first-stage landing success.
            - Built interactive visualizations with Plotly and Seaborn to explore how launch parameters relate to landing outcomes.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: pandas, icon: devicon/pandas }
            - { name: Plotly, icon: devicon/plotly }
            - { name: Seaborn, icon: devicon/seaborn }
            - { name: Jupyter, icon: devicon/jupyter }
          links:
            - text: Capstone badge
              url: https://www.credly.com/badges/2fc745a1-b5d5-4582-9348-cdf134b4b7e8
            - text: Certificate
              url: https://www.credly.com/badges/5e80beff-1b1a-4e27-96fb-c8b249561024
          figures:
            - src: uploads/projects/spacex-success-rate-by-year.png
              alt: Seaborn line chart of Falcon 9 first-stage landing success rate by year, at zero through 2013 and rising to about 90% by 2019
              title: Success Rate of Rocket Landings
              caption: Yearly first-stage landing success rate, climbing from zero before 2014 to around 90% by 2019.
            - src: uploads/projects/spacex-success-rate-by-orbit.png
              alt: Seaborn bar chart of average landing success by orbit type, with ES-L1, SSO, HEO, and GEO at 100% and GTO lowest at about 52%
              title: Success Rate of Each Orbit
              caption: Average landing success by target orbit, with ES-L1, SSO, HEO, and GEO missions landing every time.

        - title: Analyzing Website Data with The GRAMMYs
          org: The Global Career Accelerator
          date: July 2024 – August 2024
          summary: |-
            - Identified key trends and user behaviors using Python to inform content strategy and promotional initiatives by analyzing and interpreting website traffic data for The GRAMMYs.
            - Analyzed critical performance metrics with pandas, uncovering patterns and identifying areas for improvement, leading to enhanced user engagement and site optimization.
            - Conducted thorough benchmarking and competitive analysis, identifying growth opportunities and strategic advantages to position The GRAMMYs ahead of competitors.
            - Developed dynamic, interactive data visualizations using Plotly, delivering actionable insights to GRAMMYs stakeholders and facilitating data-driven decision-making.
          tools:
            - { name: Python, icon: devicon/python }
            - { name: pandas, icon: devicon/pandas }
            - { name: Plotly, icon: devicon/plotly }
            - { name: NumPy, icon: devicon/numpy }
          links:
            - text: Certificate
              url: https://www.credential.net/8156ede7-dcc7-49e1-a57c-7ebcc27c035a
          figures:
            - src: uploads/projects/grammys-pages-per-session.png
              wide: true
              alt: Plotly line chart of daily average pages per session from February 2022 to June 2023, with the Recording Academy site at a median of 2.9 pages and a peak of 11.4 on June 15, 2022, and grammy.com at a median of 2.1 with a peak of 5.8 on February 5, 2023
              title: Pages per Session
              caption: Daily engagement on the GRAMMYs and Recording Academy websites. Recording Academy visitors viewed more pages per visit, while the GRAMMYs' peak lined up with the February 2023 awards show.
            - src: uploads/projects/grammys-age-demographic.png
              wide: true
              alt: Plotly grouped bar chart of visitors by age group for grammy.com and recordingacademy.com, with 18-24 and 25-34 the largest groups and 65+ the smallest
              title: Age Demographic
              caption: Share of visitors by age group on the GRAMMYs and Recording Academy websites, built with Plotly.

        - title: Intel Sustainability Project
          org: The Global Career Accelerator
          date: June 2024 – July 2024
          summary: |-
            - Conducted thorough research using complex SQL queries to determine the best locations for new data centers based on energy availability and sustainability requirements.
            - Generated sensible conclusions and suggestions to guide the selection of sustainable and energy-efficient sites in decision-making processes.
            - Found ways to maximize the use of energy in data center operations and to harness renewable energy sources, which helped Intel meet its commitment to sustainability goals.
            - Identified places where energy output is excess, which might result in lower energy procurement costs for newly operating data centers.
            - Contributed significantly to Intel's sustainability efforts by offering data-driven insights on adoption tactics for renewable energy, all visualized on Tableau.
          tools:
            - { name: SQL, icon: devicon/microsoftsqlserver }
            - { name: Tableau, icon: custom/tableau }
          links:
            - text: Certificate
              url: https://www.credential.net/70c06f22-64c1-4694-bcb4-2ff9ce7dde34
          figures:
            - src: uploads/projects/intel-renewable-share-by-region.jpg
              alt: Tableau bar chart of renewable energy as a percentage of overall generation by U.S. region, led by the Northwest, Central, and California, with Florida lowest
              title: Renewable Energy % per Region
              caption: How much of each region's energy comes from renewable sources, as a percentage.
            - src: uploads/projects/intel-net-production-by-region.jpg
              alt: Tableau bar chart of net energy production by U.S. region, with New England and the Mid-Atlantic producing a surplus and California and New York showing the largest deficits
              title: Net Production vs Demand of Energy
              caption: Net energy production by region. Regions below zero can't keep up with their energy demand.

        - title: Company Data Analysis
          date: May 2024
          summary: |-
            - Created and managed a SQL database of over 15,000 rows to support structured, governed data access for sales and performance analysis.
            - Developed automated Python pipelines for data cleaning, transformation, and storage, ensuring consistent data quality and traceability.
            - Built Tableau reports for sales, customer behavior, and performance trends, aligning visualizations with internal business data strategies.
          tools:
            - { name: SQL, icon: devicon/microsoftsqlserver }
            - { name: Python, icon: devicon/python }
            - { name: Tableau, icon: custom/tableau }
          figures:
            - src: uploads/projects/company-data-dashboard.jpg
              alt: "Tableau dashboard: yearly revenue from 2019 to 2024 peaking at about $143K in 2022, revenue by item, and item distribution with AC units at 72% and furniture at 26%"
              title: Revenue by Year and Item
              caption: Yearly revenue peaked at about $143K in 2022, and AC units brought in 72% of all sales.
            - src: uploads/projects/company-data-sales-map.jpg
              alt: Tableau map of revenue by city across South Texas, with the largest totals in Zapata and McAllen
              title: Revenue by City
              caption: Sales mapped across South Texas, with Zapata and McAllen bringing in the most revenue.
---
