# Quick Quiz API :bulb:


[![Website shields.io](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://quick-quiz-api.herokuapp.com)
[![GitHub release](https://img.shields.io/github/release/prkhrv/Quick-Quiz-API.svg)](https://GitHub.com/prkhrv/Quick-Quiz-API/releases/)




Open Trivia Based APIs For Current Affairs and General Knowledge For UPSC aspirants. Helping a lot of Developers and EdTech Companies to Work on their Products. Updated Daily with New questions. 

## Endpoints :link:

* [Questions](https://quick-quiz-api.herokuapp.com/questions/10) : `GET`  `/questions/{noOfQuestions}`

**URL** : `/questions/{noOfQuestions}`

**Method** : `GET`

**Auth required** : NO

**Parameters**

```
{noOfQuestions} : Integer
required: true
MaxLimit : 20
Default : 10

```

## Success Response :heavy_check_mark:

**Code** : `200 OK` :heavy_check_mark:

**Content example**

```json
{
  "results": [
    {
      "incorrect_answers": [
        "Nagaland",
        "Odisha",
        "Uttarakhand"
      ],
      "question": " ‘Pakhui Wildlife Sanctuary’ is located in ",
      "correct_answer": "Arunachal Pradesh"
    }
  ]
}

```

## Error Response :x:

**Condition** : If The {noOfQuestions} Parameter is not given.

**Code** : `404 NOT FOUND` :x:

**Content** :

```html
<!DOCTYPE html>
  <html lang="en">
     <head>
       <meta charset="utf-8">
          <title>Error</title>
      </head>
   <body>
     <pre>Cannot GET /questions/</pre>
   </body>
</html>



```

### :pushpin: UPCOMING UPDATES

```
CONTRIBUTION PPROGRAM
API KEYS
```


## Developed and Maintained by

[PRAKHAR VARSHNEY](https://github.com/prkhrv) :computer:


### Please Do Leave a :star: if the APIs Helped you for your Project.




 
 
