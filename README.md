<a id="readme-top"></a>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This project was the code behind the paper

`Dunlap, D., & McCoy R. T. (2025). A Comparative Evaluation of Large Language Models’ Usage of African American Vernacular English. Manuscript under review at 8th AAAI/ACM Conference on AI, Ethics, and Society.`

The purpose of this paper was to evaluate computational usage of African-American Vernacular English (AAVE) in relation to native speaker usage. By doing so, we hope to provide a benchmark to allow LLMs to better understand and replicate authenticate usage of the dialect.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With
* [![Python][Python.com]][Python-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

For those with the computational resources (a computer with a sufficient processor (CPU), ample RAM, and enough storage space), this project could be run locally. If not, this project could easliy be run through a service like Google Colab. 
Within the project file there is a multitude of steps that should allow anyone to learn how to use the project and for what purposes it could be used for.

### Prerequisites

While this project only focused on three models, GPT-4o, Llama 3, and Gemma 2.7 - this project could easily be extended to include other models. It would require going either to the [Together API](https://docs.together.ai/docs/quickstart) or to the model of interest API

The project requires you to run the following command to run it: 

`
!pip install stanza
!pip install together
!pip install openai
`

If you are running this model locally, and not through Google Colab you will also need to run the following command:

`pip install nltk`.

Additionally, if you are looking to run the model generation part of the code, you will need to have your API keys from the models, as well as enough tokens to generate the request (could cost anywhere between $3 and $10).

### Installation into Local Server

2. Clone the repo
   ```sh
   git clone https://github.com/dejadunlap/AAVE_AI_Feature_Detection.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API for your models in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Useful examples of usage can be found within the code file.

<!-- CONTACT -->
## Contact

Deja Dunlap - [@LinkedIn](https://www.linkedin.com/in/deja-dunlap-2884b9238/) - deja.dunlap@yale.edu

Project Link: [https://github.com/dejadunlap/AAVE_AI_Feature_Detection]([https://github.com/github_username/repo_name](https://github.com/dejadunlap/AAVE_AI_Feature_Detection))

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I would like to thank the Yale Mellon May/Edward A Bouchet Fellowship and my cohort for their support during this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
