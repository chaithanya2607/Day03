# day3
QUESTION 1 For the given JSON iterate over all for loops (for, for in, for of, forEach).
ANSWER-->

QUESTION 2  Create your own resume data in JSON format.
ANSWWR-->
var resume= {
  "intro": [{
    "name": "Chaithanya Rao R",
    "label": "Programmer",
    "email": "rchaithanyaraot@gmail.com",
    "phone": "8310980104",
    "location": {
      "address": "Sri Sathya pg for ladies,Karuna Nagar, Neeladri road, Electronic city phase 1",
      "postalCode": "560100",
      "city": "Bangalore",
      "countryCode": "India",
      "state":"Karnataka"
      }
    }],

  "work": [{
    "name": "Global art",
    "position": "Course Instructor",
    "url": "https://www.globalart.in",
    "startDate": "March 5th 2022",
    "endDate": "Still working",
    "summary": "I work here as course instructor, my main work is to teach the drawing and colouring techniques and explaining the course details to the customers."
  }],
  "education": [{
    "institution": "Alliance University",
    "url": "https:www.alliance.edu.in",
    "branch":"Aerospace Engineering",
    "studyType": "Bachelor",
    "startYear": "2015",
    "endYear": "2019",
    "score": "3.7",
  }],
  "certificates": [{
    "name": "Javascript",
    "date": "31-05-2022",
    "url": "https://www.guvi.in/verify-certificate?id=5e1v0gZ4601q015li4"
  }],
  "skills": [{
    "name": "Web Development",
    "level": "Intermediate",
    "keywords": [
    "Python",
      "HTML",
      "CSS",
      "JavaScript"
    ]
  }],
  "languages": [
    "English","Kannada","Hindi","Marati","Telugu"
   ],
  "interests": [
    "Metaphysics","Drawing","Chess","Occult studies","Reading books"
   ], 
  "projects": [{
    "name": "Study,Synthesis and Testing of biocomposites",
    "description": "The project was mainly about the study ,synthesis and tsting of different biocomposites with different compositions and variations in proportions of raw materials.",
    "year":"2019"
    }],
    "internships":[{
    "company":"Mahindra Aerospace",
    "startDate": "02-07-2018",
    "endDate": "31-07-2018",
    "project":"Major Defects On Painted Parts and their Remedies",
    }]
}
console.log(resume);



