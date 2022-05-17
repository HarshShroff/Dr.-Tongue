# Dr. Tongue:

Tongue features, such as shape and color, can represent the body's internal health condition (e.g., organs, qi, blood, cold, heat) as well as the severity or advancement of illnesses, as we know. Medical professionals can distinguish clinical symptoms and select appropriate therapies by studying these characteristics. Such kind of diagnosis is dependent on practitioners' subjective eye observation, which is sometimes skewed by personal experience, lighting differences, and other factors. As a result, an objective and quantitative tongue diagnostic approach that can help practitioners' diagnosis is required. As an outcome, this work may benefit both practitioners and ordinary people by using this **Machine Learning based web application**.


## User Stories:

- A user can diagnose himself/herself on his own without going to an ENT specialist.
  - He/she will not have to take appointments.
  - This will save his/her time and provide an accurate result.
  - This will help him/her to get proper medications.

## Achievements:

This project ranked 4<sup>th</sup> at [Ideathon 2021](https://sites.google.com/gecrajkot.ac.in/ideathon-2020/), a state level competiton organized by the [Government Engineering College, Rajkot](http://www.gecrj.cteguj.in/).


## Features:

- Time saving
- Easy to use
- Accurate results


## Future Features:

- A `login/logout` feature to store user's history
- A list of possible diseases based on the detected tongue color
- Connecting the user directly to an online doctor for diagnosis
- Generating and sending the prescription to the user via e-mail or Telegram


## How to run?

1. Clone or download this repo to your system.
2. Go to `/Dr.-Tongue/ipynb/` and open `Dr_Tongue.ipynb` file with Jupyter notebook or VS Code.
3. Uncomment the first code cell and install all dependencies.
4. Follow the steps mentioned in the notebook.


## How to use?

1. After running the last cell, go to `http://127.0.0.1:7860/` from your browser **OR** use the cell output.
2. Upload or drag an image.
    - This image **should only contain the tongue image** to get proper results.
    - A sample image is available in `/Dr.-Tongue/unknown_imgs/`
3. It will take a few seconds to generate the results.


## Model performance

![Model Performance](https://github.com/HarshShroff/Dr.-Tongue/blob/master/Performance.png)


## How it looks like?

![Output](https://github.com/HarshShroff/Dr.-Tongue/blob/master/Appearance.png)
