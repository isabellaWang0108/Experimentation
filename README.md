# Experimentation

## Part 1
1. URL for control: https://wangx733.github.io/Experimentation? + (number that we assign them)
2. URL for test: https://wangx733.github.io/Experimentation/test.html? + (number that we assign them)
  
## Part2
3. URL for transprency retention test:https://wangx733.github.io/Experimentation/status.html? + (number that we assign them)
  
# Make sure when you send links to people.
1. each person got unique number
2. #in URL1 = #in URL2 for each one.
For example, person 1 receive https://wangx733.github.io/Experimentation?1 for control, https://wangx733.github.io/Experimentation/test.html?1 for test. person 2 should receive https://wangx733.github.io/Experimentation?2 for control, https://wangx733.github.io/Experimentation/test.html?2 for test, etc.

3. The number in part 2 do not need to be an extention for number in part 1, but they need to be unique still.

## email sample
Hi (their name),

I am a student at Cornell Tech and I am working with a couple of small/medium sized companies to help them recruit top talent. I came across your profile on Linkedin and I am reaching out to you to see if you would be interested in any of the following opportunities. 

- Frontend Engineer 
Employer notes: We are looking for a Front End Tech Lead to join our fast-paced team and take ownership of our front-end code.
click to apply

- Frontend Engineer 
Employer notes: Looking for immediate hire. You won’t be shooting your resume in the dark. We promise to keep you updated throughout the recruitment process and complete the process in 3 weeks.
click to apply

Let me know if you have any questions. 

Best,
(your name)

## How to calculate result?
Below will be the data sample

{
  "-LtHYNsaoggd9V9hUv_q" : {
    "id" : "https://wangx733.github.io/Experimentation/",
    "time" : 1.573343039012E9
  },
  "-LtHYw4BBDXsbM-79SMT" : {
    "id" : "https://wangx733.github.io/Experimentation/",
    "time" : 1.573343183179E9
  },
  "-LtHYyB5Gptc6Jv91l3j" : {
    "id" : "https://wangx733.github.io/Experimentation/",
    "time" : 1.573343191813E9
  },
  "-LtHZ7J-Wv8kpMLzLLKx" : {
    "id" : "https://wangx733.github.io/Experimentation/",
    "time" : 1.57334323328E9
  },
  "-LtHZBJEoL8_5ohHpMHh" : {
    "id" : "https://wangx733.github.io/Experimentation/test.html",
    "time" : 1.573343249678E9
  }
}

Group data with the same id, then pick the one with a smaller time.
The percentage of test determine the attractiveness of the transparency element.
