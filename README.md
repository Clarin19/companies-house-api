# companies-house-api
Python Individual Assessment on UK Companies House API

The purpose of this assessment is to draft two business questions and work with companies house UK API data. Explanatory analysis is used to analyse pressing questions pertaining to companies in the United KIngdom.

______________________________________________________________________________________________________________________________________________________________________

Business Question 1:
According to an investigative research conducted by the parliament of the United Kingdom in March 2022 and published in the House of Commons library on 6 December 2022, Retail and Wholesale accounts for 14% of the country’s job market, succeeding Health & Social care, and Professional and Technical sectors by a small, yet noteworthy margin.

The government is therefore interested to provide financial support to candidates who wish to launch operations in the wholesale and retail sector, which will help enforce this employability index. However, the government wishes to discuss with UOE Consulting Pvt Ltd on various static and dynamic factors which needs to be considered before committing to this allotment of significant resources to development of this industry.

UOE Consulting Pvt Ltd intends to leverage the companies house dataset, provided by the government to study operational activities of wholesale and retail firms from 2011 until 2022, and provide explanatory analysis and recommendation insights on:

Prime locations to open wholesale and retail headquarters
General active period / lifespan of firms in this sector
Trends pertaining to unfortunate cessation of wholesale and retail firms
Market scope of new firms launched during current / next fiscal year

Research Answer 1:
The government of United Kingdom is interested to financially support new operations in the wholesale and retail sector since they cater to a significant section of the job market. Prior to investing, they wish to receive recommendation insights on prime location for launching a new operation, generic lifespan and scope of wholesale and retail firms.

Companies House API data was extracted and filtered based on their SIC (Standard Industrial Classification) codes to yield 541 usable observational company data. Several pre-processing steps to convert semi-structured JSON into flat tables, handle null and extreme values were performed. It was observed that 94.36% of firms were dissolved with a mere 5.64% of firms in active or liquidation. To understand generic lifespan of firms, active period was computed, which revealed that 58.23% of wholesale and retail firms operated for a duration of 4-6 years and a mere 7.95% of total firms operated for at least 11 years, expressing less likelihood of longevity of operational units in this sector. The cessation of firms has decreased over the years by about 50-70%, with the first quarter of the year continuing to be the prime time for disruption in this sector.

Converting postal codes into geographical coordinates depicted most firms with a minimum lifespan of five years, were based off the business hub of Europe, London, with relevant links and exposure to national and international industries, followed by prominent areas such as Manchester, Birmingham and Brighton, where cost of operations is less compared to London.

______________________________________________________________________________________________________________________________________________________________________

Business Question 2:
According to a blog released by CNBC in March 2022, Transportation and Warehousing is one of the industries with an evident gender pay gap, an appalling 87 cents paid to a woman professional for every 1 dollar a male professional earns. This has alarmed the government of United Kingdom to evaluate equal opportunities within the transportation and warehousing sector, to ensure no workplace discrimination is occurring in terms of age, gender and culture.

UOE Consulting Pvt. Ltd. has been supplied with raw Companies House and Important Stakeholder API data of about 5000 companies from various sectors. Technical pre-processing is required to extract data relevant to transportation and warehousing companies, and a deep analysis on workforce distribution to ensure equal opportunities for all, which is a major concern for the government. The government seeks insights on current stakeholder statistics on the below three diversity metrics:

Age: Uniform distribution of stakeholders of varied age groups
Gender: Equal opportunities for professionals of all gender groups
Culture: Prominent stakeholder positions occupied by diverse cultural professionals

Research Answer 2:
The ongoing global issue of inequality in workplace is a pressing matter for the government of United Kingdom who wishes to reinforce equal opportunities and representation in workplace. The government seeks an analysis on current diversity in workforce in the transportation and warehousing (storage) sector.

Companies House API data was extracted and filtered based on SIC (Standard Industrial Classification) codes to yield over 146 observational company data, which was linked to Companies Important Stakeholders API data, yielding 71 stakeholder statistics. Several pre-processing steps to convert semi-structured JSON data into flat tables, handle null and extreme values were performed. Gender and age was extracted by mapping with title and date of birth.

The transportation and storage sector showed uniform distribution of stakeholders in terms of their age, indicating no visible signs of ageism in the sector. The minimum age of a person at the stakeholder position for this sector was 32, an age that is justifiable towards crucial work experience. While these results were promising, a major gender gap was observed, with male professionals claiming 76% of the important stakeholder positions, while females occupied merely 17% of positions. Furthermore, 78.57% of stakeholders were natives followed by a minute representation of 5.71% by the Dutch and Polish communities. There was no representation from Asians, Africans, and Hispanics, to name a few. A detailed investigation on unfair practices, if any, must be conducted in this sector, to ensure equal opportunities for prominent positions are available to professionals regardless of their gender and culture.

______________________________________________________________________________________________________________________________________________________________________
