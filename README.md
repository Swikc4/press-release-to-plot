<a id="readme-top"></a>

<br />
<div align="center">
  <h3 align="center">Press Release to Plot</h3>
  <p align="center">
    REST API pipeline that finds and maps location-related business events in SEC EDGAR filings - a CIS 3120 team project at Baruch College
    <br />
    <a href="https://github.com/Swikc4/press-release-to-plot"><strong>Explore the repo »</strong></a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#files-in-this-repository">Files in This Repository</a></li>
    <li><a href="#what-the-team-found">What the Team Found</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#full-team-submission">Full Team Submission</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

Academic team analysis completed for CIS 3120 Programming for Analytics at Baruch College in Spring 2026.

Our team compared location related business events in the Financial Services and Travel and Hospitality industries. The workflow used SEC EDGAR filings, Python, REST API requests, an LLM based classification step, geocoding, pandas, and Folium.

I was the Financial Services Pipeline Lead for Team 11. My teammates were Imran Aslam, Travel and Hospitality Pipeline Lead, and Gabriel Asimakopoulos, Comparison and Visualization Lead and Integrator. For the Financial Services side, I worked with the industry ticker list and search phrases and helped test the pipeline across different time windows.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
* ![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
* ![SEC EDGAR](https://img.shields.io/badge/SEC%20EDGAR-003A70?style=for-the-badge)
* ![Folium](https://img.shields.io/badge/Folium-77B829?style=for-the-badge)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Files in This Repository

* `financial_services_config.py` contains the final Financial Services configuration used by Team 11: 14 tickers and 40 search phrases.
* `team_submission/methodology.md` contains our final methodology.
* `team_submission/reflection.md` contains our final comparative reflection.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## What the Team Found

The results showed how much search-phrase design affects what the pipeline finds. The seeded ticker lists were narrow: out of 250 raw SEC search candidates per industry over 360 days, only 1 matched the seeded Financial Services list and only 3 matched the Travel and Hospitality list. Expanding each industry to 40 search phrases raised the number of qualifying, geocodable events from 1 to 38 in Financial Services and from 3 to 11 in Travel and Hospitality.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

`financial_services_config.py` is a configuration module rather than a standalone script. It is imported by the Team 11 analysis pipeline (linked below) to set the Financial Services ticker list and SEC EDGAR search phrases. To see the pipeline in action, open the Team 11 notebook and Folium map in the team repository. The pipeline requires Python 3 with pandas, requests, and Folium.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Full Team Submission

The complete Team 11 notebook and interactive map are preserved in our team repository. I link to the full team files rather than presenting my teammates' work as solely my own.

* [Team 11 Jupyter notebook](https://github.com/GAsimakopoulos682/cis3120-spring2026/blob/main/notebooks/MP03_Notebook_team_11.ipynb)
* [Team 11 Folium map](https://github.com/GAsimakopoulos682/cis3120-spring2026/blob/main/maps/mp03_map_team_11.html)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Swikriti KC - [LinkedIn](https://www.linkedin.com/in/swikriti-kc/)

Project Link: [https://github.com/Swikc4/press-release-to-plot](https://github.com/Swikc4/press-release-to-plot)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* CIS 3120 Programming for Analytics, Baruch College (Zicklin School of Business)
* SEC EDGAR (U.S. Securities and Exchange Commission)
* Team 11: Imran Aslam and Gabriel Asimakopoulos
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
