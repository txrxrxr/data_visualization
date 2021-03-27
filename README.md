<!-- PROJECT LOGO
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Best-README-Template</h3>

  <p align="center">
    An awesome README template to jumpstart your projects!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>
</p>
-->


<!-- TABLE OF CONTENTS 
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)
-->


<!-- ABOUT THE PROJECT -->
## Data Visualization of COVID-19 Vaccination Coverage in Canada
Data Visualization of COVID-19 Vaccination Coverage in Canada

This project focuses on the questions of interest:
* What is the number of populations that have received only one dose (per province and per month)? 
* We built a data visualization project to visualize the COVID-19 vacci-nation coverage across each province in Canada. 
* What is the comparison of vaccination coverage between two provinces (per month)?
* We built a data visualization project to visualize the COVID-19 vacci-nation coverage across each province in Canada based on Django and React. 

### Built With and Dataset
* [Django](https://www.djangoproject.com/)
* [React](https://reactjs.org/)
* [Dataset: National vaccination coverage](https://health-infobase.canada.ca/covid-19/vaccination-coverage/)

### Prerequisites
```sh
1. Clone the repo
2. $ cd data_visualization/mysite
3. $ virtualenv venv --python=python3
4. $ source venv/bin/activate
5. $ pip install -r requirements.txt
```

### Migrate and Run the back-end Server
```
1. $ python manage.py makemigrations
2. $ python manage.py migrate
3. $ python manage.py runserver
```

### Start front-end client page
```
1. $ cd my-app
2. $ npm install
3. $ npm start
```

### Interact with the data visualization system in your browser
```
- Check the vaccine coverage from the perspective of population taking 1 does and population taking 2 doses for one province in a specific month:
```
![1](https://github.com/kuangzijian/Image-Stitching-and-Perspective-Correction/blob/main/results/line_detection.png) 

```
- Compare the vaccine coverages between two provinces in a specific month:
```
![1](https://github.com/kuangzijian/Image-Stitching-and-Perspective-Correction/blob/main/results/line_detection.png) 

```
- Display the detail of the dataset (http://localhost:3000/detail):
```
![1](https://github.com/kuangzijian/Image-Stitching-and-Perspective-Correction/blob/main/results/line_detection.png) 


## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

## References
Django: https://www.djangoproject.com/
React: https://reactjs.org/
Dataset: National vaccination coverage: https://health-infobase.canada.ca/covid-19/vaccination-coverage/

