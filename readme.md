<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/KaProDes/Movie_Pundit">
    <img src="./source/favicon.ico" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Movie Pundit</h3>

  <p align="center">
    Find your next flick by asking the (almost) all-knowing Movie Pundit
    <br />
    <a href="https://github.com/KaProDes/Movie_Pundit/source"><strong>Jump to Project Source »</strong></a>
    <br />
    <br />
    <a href="https://movie-pundit.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/KaProDes/Movie_Pundit/issues">Report Bug</a>
    ·
    <a href="https://github.com/KaProDes/Movie_Pundit/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->

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
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#acknowledgments">Acknowledgments</a></li>
</ol>

<!-- ABOUT THE PROJECT -->

## About The Project

![Movie Pundit Action](./assets/demo_movie_pundit.gif)

There are many great streaming services to watch movies online in todays day and age. However, their build in content suggestion system is quite a bit broken and often times distracting, as convenient as it may be. This was the inspiration behind this Project. To iteratively build the best Movie Recommendation System that asks you what type of movie you would like to watch, no tell you what you should be watching in an intrusive way.

Why use Movie Pundit:

-   Fast and Seamless with a catalogue of 5000+ movies to boot
-   Integration with TMDB API allows you quicky read up the entire summary from IMDB itself
-   Created by movie buffs. We have painstakingly created the Content Recommendation Model from Scratch <a href="https://colab.research.google.com/drive/148dyD-qc0W6bPDtMAcHifosqFqbdX9SG?usp=sharing">Know More »</a>

Of course, building a recommendation system is a continuous process and requires iterative improvements and matures over time. We will be updating the model on the backend per the issues/user feedback and we aim to make the most authentic recommender on the internet!

<img src="https://i.ibb.co/VH6wcLH/2021-12-14-13-29-22-Settings.png" alt="Movie Pundit Home" width="60%">

Visit <a href="https://movie-pundit.herokuapp.com/">Movie Pundit</a> to check it out now!

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

This project is made with :

-   [Bootstrap 5](https://getbootstrap.com)
-   [JQuery](https://jquery.com)
-   [Streamlit](https://streamlit.io/)
-   [Pandas](https://pandas.pydata.org/)
-   [Numpy](https://numpy.org/)
-   [Pickle](https://docs.python.org/3/library/pickle.html)
-   [nltk](https://www.nltk.org/)
-   [sklearn](https://scikit-learn.org/stable/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Before you start working on this project/fork it, it is highly recommended that you check out how the model was developed here : [Model ipynb](https://colab.research.google.com/drive/148dyD-qc0W6bPDtMAcHifosqFqbdX9SG?usp=sharing)

We can clone the entire project
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

-   pip
    ```sh
    python -m pip install –upgrade pip
    ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [developers.themoviedb.org/3/getting-started/authentication](https://developers.themoviedb.org/3/getting-started/authentication)
2. Clone the repo
    ```sh
    git clone https://github.com/KaProDes/Movie_Pundit.git
    ```
3. Install pip packages (It is recommended to this in a `venv`)
    ```sh
    pip install requirements.txt
    ```
4. Edit this line by entering your API key in `app.py`
    ```py
    my_api_key = "ENTER YOUR API_KEY"
    ```
5. Launch the Project by writing
    ```sh
    streamlit run app.py
    ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Your Name - [@KapProDes](https://leetcode.com/KapProDes/) - deshmukhkapil4@gmail.com

Project Link: [https://github.com/KaProDes/Movie_Pundit](https://github.com/KaProDes/Movie_Pundit)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Special thanks to all my teachers and mentors. I have made this project as part of my Social Network Analysis and Big Data Analytics practical learning.

-   [Colt Steele](https://github.com/Colt)
-   [Krish Naik](https://www.youtube.com/user/krishnaik06)
-   [CampusX](https://www.youtube.com/channel/UCCWi3hpnq_Pe03nGxuS7isg)
-   [Data Professor](https://www.youtube.com/c/DataProfessor)
-   [Applied AI](https://www.appliedaicourse.com/)

<p align="right">(<a href="#top">back to top</a>)</p>
