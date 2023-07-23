<br/>
<p align="center">
  <h3 align="center">
    FastAPI Project
  </h3>

  <p align="center">
    Learn to create Coroutines, Events, and Message-Driven Transactions by Building Newsstand Management System Prototype
    <br/>
  </p>
</p>

<p align="center">
  <p align="center">
    <img src="https://img.shields.io/github/downloads/dzalhaqi/fastapi-asynchronus-newsstand-management-system/total"/>
    <img src="https://img.shields.io/github/contributors/dzalhaqi/fastapi-asynchronus-newsstand-management-system?color=dark-green"/>
    <img src="https://img.shields.io/github/forks/dzalhaqi/fastapi-asynchronus-newsstand-management-system?style=social"/>
    <img src="https://img.shields.io/github/issues/dzalhaqi/fastapi-asynchronus-newsstand-management-system"/>
    <img src="https://img.shields.io/github/license/dzalhaqi/fastapi-asynchronus-newsstand-management-system"/>
  </p>
</p>

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Description](#description)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About The Project

### Description

This prototype serves as a sophisticated platform designed to facilitate the management, sales, and distribution of newspapers. It caters to multiple newspaper organizations, enabling them to handle marketing, sales, and content management seamlessly. To access the system, each organization is required to register their respective representative(s) and obtain login credentials upon approval. Once approved, these representatives have the authority to manage and approve the content of their daily issues, aligning them with the agreed budget and guidelines. The application includes essential services, such as periodic sales monitoring and the creation of a pool of messengers employed to deliver newspapers to various outlets. Additionally, the system offers customer tracking features, allowing organizations to keep tabs on customers and the outlets where newspapers are purchased. This prototype stands as an initial endeavor in establishing an efficient newspaper management portal using core features which is **asynchronus API**. 

## Built With

Application deployed is build with **Python** using **FastAPI** library 

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* python

for Windows OS
```sh
python --version 
```

for Unix Based OS (Linux, MacOS, etc)
```sh
python3 --version 
```

* git

```sh
git --version 
```

> note: if you don't have python installed, you can download it [here](https://www.python.org/downloads/) and if you don't have git installed, you can download it [here](https://git-scm.com/downloads)

### Installation

1. Clone the repo

```sh
git clone https://github.com/Dzalhaqi/fastapi-asynchronus-newsstand-management-system.git
```

2. Create python environment

```sh
python -m venv env
```

3. Activate python environment

* for Windows OS
```sh
env\Scripts\activate
```

* for Unix Based OS (Linux, MacOS, etc)
```sh
source env/bin/activate
```

4. Install python library

```sh
pip install -r requirements.txt
```

5. Run the FastAPI server with uvicorn (default port 8000)

```sh
uvicorn main:app --reload
```

## License

Distributed under the MIT License. See [LICENSE](https://github.com/dzalhaqi/fastapi-asynchronus-newsstand-management-system/blob/main/LICENSE) for more information.

## Acknowledgements

* [Muhammad Dzalhaqi](https://github.com/dzalhaqi/)
