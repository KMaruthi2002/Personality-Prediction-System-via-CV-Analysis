# WeEmploy

The project aims to develop a prototype of a platform that eradicates the traditional way of employment which comes with the need to manually go through numerous applications and CVs to find out what suits the particular requirement of the job being offered. WeEmploy seeks a more efficient way to short-list submitted candidate CVs from a large number of applicant providing a consistent and fair CV ranking policy, which can be legally justifed. This system will help the HR department to easily short-list the candidate based on the CV ranking policy.

[![star this repo](https://githubbadges.com/star.svg?user=philkam&repo=AI_Personality-Prediction-System-Through-CV-Analysis&style=default&color=fff&background=4c3)](https://github.com/philkam/AI_Personality-Prediction-System-Through-CV-Analysis)
[![fork this repo](https://githubbadges.com/fork.svg?user=philkam&repo=AI_Personality-Prediction-System-Through-CV-Analysis&style=default&color=fff&background=4c3)](https://github.com/philkam/AI_Personality-Prediction-System-Through-CV-Analysis/fork)

## Table of Contents
* [Pre-requisites & Development Libraries](#pre--requisites-&-development-libraries)
* [Installation](#installation)
* [Instructions](#instructions)
* [Motivation](#motivation)
* [How To Setup The System](#how-to-set-up-the-system)


## Pre-requisites & Development Libraries


To install WeEmploy you'll need pip and Git. It also uses a some Python packages (NumPy, SciPy and Matplotlib) but these should be taken care of by the installation process.

| Software | Version |
| ------ | ------ |
| Python 3 | 3.9.6 |
| Pandas | 0.25.1 |
| Snscrape | 0.4.3 |
| Flask | 2.1.2 |
| Google Chrome | 102.0.5005.115 |



## Installation

You can install WeEmploy by cloning the repository:

```sh
git clone https://github.com/philkam/AI_Personality-Prediction-System-Through-CV-Analysis.git
```

## Instructions

* Clone the [repository](#installation)

* Set up a virtual environment. See [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments) for more details. Don't forget to activate the virtual environment.

* Install all required libraries through requirements.txt

```sh
pip install requirements.txt
```

* Run your local server ( WAMP, XAMPP etc)

* Now run the Flask app app.py.

```sh
python app.py
```

* In your browser open http://localhost:5000 (or :{port-number} as specified by the Flask's development server)


## Background 

There are various tests that help to determine personality types such as the Big Five, Rorschach test, and MBTI test. In this project, prediction of personality is done by considering the MBTI test.

The MBTI personality classification system grew out of Jungian psychoanalytic psychology as a systematization of archetypal personality types used in clinical practice. The system is divided along four binary orthogonal personality dimensions, altogether comprising a total of 16 distinct person.

### The dimensions are as follows

* Extraversion (E) vs Introversion (I): a measure of how much an individual prefers their outer or inner world.

* Sensing (S) vs Intuition (N): a measure of how much an individual processes information through the five senses versus impressions through patterns.

* Thinking (T) vs Feeling (F): a measure of preference for objective principles and facts versus weighing the emotional perspectives of others.

* Judging (J) vs Perceiving (P): a measure of how much an individual prefers a planned and ordered life versus a flexible and spontaneous life

## Components of the Application
* Login and Registration
* Aptitude Assessment
* Personality test
* CV analysis


## Aptitude Assessment
The aptitude assessment helps understand the underlying patterns of candidates interest and predict the stream that the candidate is interested in.
Understanding a candidates inherent aptitude is very crucial for an organisation. Candidates can test their aptitude after which a report is generated which can assess a candidate's interest. Based on this, the Human Resource Manager can place a candidate in the right team and point out the right candidate for a particular job.

#### Assessment
This section of the application allows the registered candidates to attend the aptitude assessment. The candidate registers through a portal, fills in the compulsory profile information and logs on to the application. The student views the assessment report.  The application allows the human resource personnels to prepare the set of questions. Assigning of questions to the candidates is done automatically, though the question paper is prepared by a human resource personnel. It also allows the personnels to manage students and also to edit their own profile. The personnel is registered by the Human Resource Manager.


## Personality Test


## CV Analysis


## Results


## Disclaimer

WeEmploy is still an experimental prototype however instances fit for specific use cases can be spawned and developed for your use. In order to contact us for such an endeavor please check out the contributors for this project.
