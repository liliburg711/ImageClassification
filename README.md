# ImageClassification
> A Restful API Practice. ImageClassification API use machine learning to classify images.

## API Functions
> Register: user can register username and password, and API can verify user exist or wrong password
* Method: POST
* Status code: 200 OK/ 301 invalid username / 302 invalid password
> Classify : user can provide a image location (url of jpg file), API can classify the things such as animal, human, non-human things... in images. And API set up the tokens the user have, user have to pay tokens to classify image. 
* Method: POST
* Status code: 200 OK/ 301 invalid username / 302 invalid password / 303 out of tokens
> Refill : if user has enough tokens, API admin can refill the tokens
* Method: POST
* Status code: 200 OK/ 301 invalid username / 304 invalid admin_password

## Technologies
> Backend
* Programming Language : Python 3.6.7
* Framework : flask

> Database
* MongoDB 4.4.2

> Library
* Tensorflow / model: Inception v3
* Numpy
* Bcrypt


> Deployment
* Docker
* AWS EC2
