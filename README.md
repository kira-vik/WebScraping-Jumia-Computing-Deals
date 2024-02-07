<h1 align="center">Web Scraping with Python: Jumia Computing Deals</h1>
<a name="readme-top"></a>

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
    <li><a href="#author">Author</a></li>
  </ol>
</details>

<!--ABOUT THE PROJECT-->
## About the Project

![jumiascraping](https://github.com/kira-vik/WebScraping-Jumia-Computing-Deals/assets/35596661/5c0642d4-827b-44be-8b13-ff1458bf99f3)

This project builds on the knowledge acquired from completing [this](https://github.com/kira-vik/WebScraping-with-Python) project, which acted as a learning point for web scraping using the BeautifulSoup library. The scraped data is held in a Pandas Dataframe, which is then exported into an external file, which in this case is a CSV file. The web scraping playground used for this project is [www.jumia.co.ke/mlp-black-friday-h-computing-deals](https://www.jumia.co.ke/mlp-black-friday-h-computing-deals/), where we retrieve details of products in the computing deals catalog such as the product title, the current and old price, the percentage discount on the product, the star rating, and the verified ratings count for the product. This project helps polish skills and understanding of the mechanism of web scraping.

This project has been developed in VS Code, but it is okay to use your code editor of choice.

### Built With

- VS Code
- Python 3.11.0
- Jupyter Notebooks

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>

<!--GETTING STARTED-->
## Getting Started

### Prerequisites

Here are a few of the resources that you will need to properly set up the project and get it running in your system.

- [Python](https://www.python.org/downloads/)
- A code editor
- Jupyter Notebooks
- Alternatively, check out [Google Colab](https://colab.google/)

### Installation

Clone the repository by running the following command in your project directory:

```bash
git clone {project-link}
```

You can open the cloned repository in VS Code using the command in your project directory:

```bash
code . {project-path}
```

Set up a virtual environment to keep necessary dependencies isolated to this particular project:

```bash
python -m venv {virtual_env_name}
```

Activate the virtual environment:

- On Windows:

```bash
{virtual_env_name}\Scripts\activate
```

- On macOS/Linux:

```bash
source {virtual_env_name}/bin/activate
```

Download the required libraries using the command in your project terminal:

```bash
pip install -r requirements.txt
```

You can run the code cell by cell as is the case with Jupyter Notebooks.

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>

<!--AUTHOR-->

## Author

Victor Weke - @[kira-vik](https://github.com/kira-vik)

Project Link: [WebScraping-with-Python](https://github.com/kira-vik/WebScraping-with-Python)

> DON'T PRACTISE UNTIL YOU GET IT RIGHT, PRACTISE UNTIL YOU *NEVER* GET IT WRONG
>
> By *John Flanagan*

<p align="right">
     [<a href="#readme-top">back to top</a>]
</p>
