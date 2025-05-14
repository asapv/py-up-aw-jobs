# py-up-aw-jobs

## Project Description

This project develops a job offer classification system in Peru using web scraping, natural language processing (NLP), and supervised learning techniques. Its goal is to extract, process, and classify job advertisements from various web sources (such as Bumeran and Computrabajo) according to the National Classification of Occupations (CNO) 2015 established by the Ministry of Labor and Employment Promotion of Peru.

### Context and Relevance

In the current context of the Peruvian labor market, characterized by sustained economic growth, the creation of approximately 470,000 new jobs is projected by 2025. However, the heterogeneity of online job postings makes it difficult to build a unified view of national labor trends.

This project seeks to transform scattered job offer information into structured and comparable knowledge, facilitating decision-making in public policies related to employment and human talent development in the country.

## Project Methodology

The system implements an approach in three main phases:

- **Data Extraction**: Automated web scraping from Peruvian job portals such as Bumeran and Computrabajo.
- **Processing**: Analysis and structuring of the information using NLP techniques.
- **Classification**: Categorization of job offers according to CNO 2015 using supervised learning algorithms.

## Repository Structure

```
📦 proyecto-clasificacion-empleo/
├── 📁 src/                             # Project source code
│   ├── 📁 bumeran/                     # Bumeran scripts
│   │   └── Bumeran_scraping.ipynb      # Notebook with scraping script
│   └── 📁 computrabajo/                # Computrabajo scripts
│       ├── computrabajo.ipynb          # Scraping notebook
│       └── procesamiento.ipynb         # Processing notebook
├── 📁 data/                            # Project data
│   ├── 📁 raw/                         # Raw data
│   │   └── 📁 computrabajo/            # Raw Computrabajo data
│   │       ├── job_details.json        # Unprocessed data (JSON)
│   │       └── ultimo_scraping.txt     # Log of last scraped link
│   └── 📁 processed/                   # Processed data
│       ├── 📁 bumeran/                 # Processed Bumeran data
│       │   └── bumeran_empleos.xlsx    #  Extracted Excel data
│       └── 📁 computrabajo/            # Processed Computrabajo data
│           └── job_results.csv         # Processed results in CSV
├── 📁 docs/                            # Documentation
│   └── paper.pdf                       # Project academic paper
└── 📄 README.md                        # Repository content
```
## Expected Benefits

- **For the Government**: Better capacity to formulate and implement employment policies based on real market data.
- **For the Education Sector**: Identification of gaps between educational offerings and labor market needs.
- **For Workers**: Greater insight into sectors with talent demand and required skills.

## Team Members

* **Mario Miguel Auqui Cubas**  
  Department of Engineering, Universidad del Pacífico.  
* **Jhoan Leandro Vargas Collas**  
  Department of Engineering, Universidad del Pacífico.  
* **Paulo Giusepe Verde Huayaney**  
  Department of Engineering, Universidad del Pacífico.  
