<img src="https://github.com/pk-aduyaw/Indian-startup-funding-analysis/assets/148882212/d852a4cb-bd2d-4363-ae51-7239b0c2055c" height=350 width=1000>

<h1 align='center'>Indian Startup Funding Analysis</h1>

<h2>Overview</h2>

This project focuses on investigating the `Indian Startup Ecosystem` in order to propose the best course of action for teams trying to venture into the ecosystem. According to [ADITYA SINGH MANN](https://www.orfonline.org/expert-speak/indian-startup-ecosystem/), India's startup ecosystem is the third largest startup ecosystem in the world with a growing economy, increasing technological advancements disrupting traditional business models, and a large pool of talented individuals.
<p>The scope for Indian startups is immense in various sunrise and sustainable development sectors such as green energy, health tech, deep tech, and clean mobility. Coupled with this is the government’s support, with initiatives such as the Startup India programme, Atal Innovation Mission, and Production-Linked Initiative schemes (PLI) that create an environment conducive to their success and growth.</p>

<p>There were four different datasets which were sourced through different means and put together in order to deal with inconsistencies and also to have a complete dataset to work with while answering analytical questions for insights into the ecosystem.</p>

<h2>Installation</h2>

Getting started on this project requires that you have `python version 3.9 or recent versions` on your local machine. The packages needed to complete this project are all contained in the `requirements.txt` file.

Install the required modules by running this command in your terminal

```bash
pip install -r requirements.txt
```

<h2>Data Understanding</h2>

The final dataset used for visualization had eleven columns and these are the descriptions of the columns:

* Company_Brand: The name of the startup
* Founded: The year in which the startup was founded
* HeadQuarter: The headquarters location of the startup
* Sector: The industry classification sector which the startup falls under
* What_it_does: The service the startup renders
* Founders: The people responsible for the startup
* Investor: Individuals or firms who give funding to startups
* Amount($): The funds received from investors in dollars
* Stage: The stage of funding reached by startup
* Funding_Year: The year in which the startup received funding
* Tech_Status: Information on whether a startup is a tech startup or not

<h3>Data Cleaning Process</h3>

1. Dealt with duplicates and missing values in the dataset
2. Dropped redundant columns in the dataset
3. Checked the individual columns for inconsistencies and dealt with these inconsistencies
4. Feature-generated new columns in the dataset to help give me perspective to the data

The detailed procedures can be found in the jupyter notebook.



<h2>References</h2>

- https://www.orfonline.org/expert-speak/indian-startup-ecosystem/
- [Global Standard Industry Classification](https://www.msci.com/our-solutions/indexes/gics#:~:text=GICS%C2%AE%20is%20an%20industry,consistent%20and%20exhaustive%20industry%20definitions.)


<h2>Author</h2>
Prince K. A. Aduyaw
