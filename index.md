---
layout: default
title: "Beyond SQL Workshop 2026 — AI for Complex Data Management"
description: "Beyond SQL Workshop 2026 (co-located with ICDE) brings together researchers and practitioners in AI, data management, and natural language interfaces to explore benchmarks, advanced SQL analytics, and emerging techniques for complex data workflows."
keywords: "Beyond SQL, workshop, ICDE 2026, natural language to SQL, complex data management, AI, benchmarks, data systems"
permalink: /

# Open Graph / Social
og_title: "Beyond SQL Workshop 2026"
og_description: "A research workshop on AI-driven analytics, benchmarks, and advanced natural language interfaces for complex SQL and data workflows."
og_image: "/BeyondSQL_logo.png"
og_type: "website"
---

<style>
  table {
    border-collapse: collapse;
  }
  table, th, td {
    border: none !important;
  }

  th {
    background-color: #f6f8fa;
    font-weight: 600;
  }
  
  tr:nth-child(even) {
    background-color: #fafafa;
  }

  th, td {
  padding: 10px 12px;
  border-bottom: 1px solid #e5e7eb;
  border-left: none;
  border-right: none;
  border-top: none;
  }
  
</style>

# Beyond SQL: AI for Complex Data Management 
---

<!-- Navigation bar -->
<div style="text-align:center; margin-bottom: 2em;">
  <a href="#objectives">Objectives</a> •
  <a href="#format">Format</a> •
  <a href="#call">Call for Papers</a> •
  <a href="#dates">Dates</a> •
  <a href="#submissions">Submissions</a> •
  <a href="#program">Program</a> •
  <a href="#organization">Organization</a>
</div>

---

## <a name="objectives"></a> Objectives

There has been a tremendous amount of work in the space of converting natural language to SQL queries.  While this work is very valuable to business users, enterprise data management has many complex uses of SQL that are less actively covered by current work.  Examples are querying structured and unstructured data, knowledge graphs, property graphs, performing extract load transform workloads, remediating complex SQL queries as application demands change, etc. As AI is increasingly used to transform simpler querying workloads, there is an opportunity to apply them in these other aspects of data management. We aim to bring together researchers exploring these diverse topics together to promote cross-fertilization and sharing of techniques that may transfer well from one domain to the other.

## <a name="format"></a> Format
Beyond SQL will be held as a half-day workshop at [ICDE 2026](https://icde2026.github.io/). The proceedings of all workshops will be published jointly alongside with the conference proceedings. 

The workshop accepts regular research papers and industrial papers of the following types:
- Full research papers: up to **8 pages** + references (no appendix)
- Short paper: up to **4 pages** + references  (no appendix)
- Extended abstract papers: up to **2 pages** + references (no appendix)

## <a name="call"></a> Call for Papers

**Audience**: Our workshop encourages participation from researchers in data management, AI, natural language processing, vision and semantic web working on a wide range of problems relevant to these topics. We hope that this will constitute a single reference point for the researchers and practitioners working in that area and help form new collaborations. We also aim to provide a venue for researchers from industry and practitioners present use cases and discuss their needs in addressing real-world problems and large-scale solutions especially with respect to newer topics such as data products.

**Topics of Interest** include but are not limited to: 
- ETL/ELT workload processing
- SQL remediation
- SQL extensions
- Structuring unstructured data at scale
- Querying other structured data (RDF graphs, property graphs, JSON).
- Linking structured and unstructured data at scale
- Creation of data products
- Data governance and data contracts
- SQL editing for changing application requirements
- From data to report generation, hypothesis testing
- Benchmarks on any of the topics above

**Novelty**: Submissions must present original work that has not been previously published or accepted at any other conference or workshop. Contributions should demonstrate substantial novelty and provide meaningful advancement beyond prior work.

## <a name="dates"></a> Dates

|             | Deadline |
| ----------- | ----------- |
| Paper Submission      | February 16th, 2026     |
|  Notification of acceptance:     | March 2nd, 2026        |
|  Camera-ready copy due:     | March 9th, 2026      |
|  **Workshop day:**     | **May 4th, 2026**     |
| ICDE Main Conference:     | May 5-8th, 2026       |


## <a name="submissions"></a> Submissions
Submissions will be submitted over OpenReview and will be reviewed in a single-anonymous manner.

Submit your paper at: [https://openreview.net/group?id=IEEE.org/ICDE/2026/Workshop/Beyond_SQL](https://openreview.net/group?id=IEEE.org/ICDE/2026/Workshop/Beyond_SQL)

Template: Manuscripts must be prepared in accordance with the [IEEE format](https://www.ieee.org/conferences_events/conferences/publishing/templates.html) that is also used for the main ICDE conference.

## <a name="program"></a> Conference Program

|   Time      | Progam | Speaker |
| ----------- | ----------- | ----------- |
| 11:00    | Keynote 1 - BIRD-SQL: Towards Automatic Data-Centric Code Generation | Reynold Cheng   |
| 12:10    | Cost Trade-offs of Reasoning and Non-Reasoning Large Language Models in Text-to-SQL [[pdf](papers/BeyondSQL_2026_Cost_Trade_offs_of_Reasoning_and_Non_Reasoning_Large_Language_Models_in_Text_to_SQL.pdf)] | Saurabh Deochake, Debajyoti Mukhopadhyay |
| 12:30    | Lunch Break |  |
| 14:00    | Keynote 2  | Aditya Parameswaran |
| 14:55    | Automatic End-to-End Data Integration using Large Language Models [[pdf](papers/BeyondSQL_2026_Automatic_End-to-End_Data_Integration.pdf)] | Aaron Steiner, Christian Bizer |
| 15:15    | Short Break |  |
| 15:20    | Towards Executing Sloppy SQL Queries Over Tabular Data Lakes [[pdf](papers/BeyondSQL_2026_Executing_Sloppy_SQL_Queries_over_Tabular_Data_Lakes.pdf)] | Jan-Micha Bodensohn, Jakob Steinke, Carsten Binnig |
| 15:40    | How Far Can They Map? Probing LLM Capabilities for Cross-Schema SQL Generation [[pdf](papers/BeyondSQL_2026_Cross_Schema_SQL_Generation.pdf)] | Mohammadreza Daviran, Davood Rafiei |
| 16:00    | Closing |  |

### Keynotes:

**BIRD-SQL: Towards Automatic Data-Centric Code Generation** - [Reynold Cheng](https://www.reynold.hku.hk/) (University of Hong Kong (HKU))

**Abstract:** Database systems, which provide various operations for defining and querying data, enable large-scale AI systems and intelligent applications in various domains. Due to recent advances in large language models (LLMs), automating database operations through code generation has become increasingly attainable. This capability has given rise to a new paradigm—Data-Centric Code Generation (DCCG)—which aims to build systems that can automatically understand, manipulate, and reason over data.
To realize DCCG, I will discuss our team’s effort in building benchmarking systems, including BIRD-SQL, a large-scale Text-to-SQL benchmark on real databases, and SWE-SQL, which gauges the ability that an LLM resolves user SQL issues. These benchmarks, widely used in the industry, reveal hallucination and other issues faced by LLMs. To address these challenges, I will present our work in graph-aware reasoning, SQL correction, and multi-turn tabular data analysis. They aim to evolve LLMs from static code generators into autonomous, trustworthy agents that can understand and generate data-driven software systems.

**Bio:** Prof. Reynold Cheng is the Division Head and Professor (AI & Data Science), at the School of Computing and Data Science in the University of Hong Kong (HKU) established in 2024. He is a Steering Committee Member of the HKU Musketeers Foundation Institute of Data Science. He is an academic advisor to the College of Professional and Continuing Education of HKPU. He was an Associate Dean of Engineering in 2022-24. His research interests are in data science, big graph analytics and uncertain databases. 
Professor Cheng is named the AI 2000 Most Influential Scholar Honorable Mention in Database in 2023 to 2025. He received the ACM Distinguished Membership Award and the HKU Outstanding Research Student Supervisor Award in 2023. He was listed as the World’s Top 2% Scientists by Stanford University in 2022.  He received the SIGMOD Research Highlights Reward 2020, International Exhibition of Inventions Geneva Award (2026), HKICT Awards (2021, 2023), HKU Knowledge Exchange Award (2024), HKU Engineering Knowledge Exchange Award (2024, 2021), HKU Engineering Best Teaching Award (2023, 2024), and HKU Outstanding Young Researcher Award 2011-12. He received the Universitas 21 Fellowship in 2011, and Hong Kong Polytechnic University Computing Performance Awards (2006, 2007).  He was a PC co-chair of IEEE ICDE 2021. He is on the editorial board of PVLDB, ACM TSAS, IS, DAPD, and DSEJ.

**Keynote 2** - [Aditya Parameswaran](https://people.eecs.berkeley.edu/~adityagp) (University of California, Berkeley)


## <a name="organization"></a> Organization
For questions, please contact: solashirai(at)ibm.com

Beyond SQL is organized by: 
- Oktie Hassanzadeh (IBM Research)
- Kavitha Srinivas (IBM Research)
- Liane Vogel (TU Darmstadt)
- Sola Shirai (IBM Research)
- Liana Patel (Stanford University)

###  Program Committee
- Alon Halevy (Google Cloud)
- Haonan Wang (Columbia University)
- Paolo Papotti (EURECOM)
- Madelon Hulsebos (CWI)
- Jan-Micha Bodensohn (TU Darmstadt)
- Makbule Gulcin Ozsoy (Neo4j)
