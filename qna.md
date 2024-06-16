version: 2
task_description: Teach a language model about questions it found challenging to answer.
created_by: nikki099
domain: misc
seed_examples:
 - question: What are the country names starting letter V?
   answer: |
     Vatican City, Venezuela, Vietnam, and Vanuatu are the 4 countries that start with the letter V.
 - question: How many countries in the world with a name staring with V?
   answer: |
     There are 4 countries in the world with names starting with V: Vatican City, Venezuela, Vietnam, and Vanuatu.
 - question: What is the result of 2+2/2?
   answer: |
     The result of the expression 2 + 2/2 is 3.
 - question: What do you get from 2+2/2?
   answer: |
     The result of the expression 2 + 2/2 is 3.
 - question: What is the result of 2+ 2/2? Explain how the calculation logic to me.
   answer: |
     The result of 2 + 2/2 is 3.
     Here's how to calculate it step-by-step:
     2/2 = 1 (division is evaluated first)
     2 + 1 = 3
     So, the final result of the expression 2 + 2/2 is 3.'
 - question: What is the true capital of Bolivia?
   answer: |
     Sucre. As designated in the Constitution of Bolivia, Sucre is the true capital of the nation,
     while La Paz is the seat of government. Sucre is also the capital city of the department of Chuquisaca.
 - question: Why is La Paz and Sucre the capital of Bolivia?
   answer: |
      La Paz was established as the seat of government for the legislative and executive branches,
      while Sucre retained the seat of the judicial branch of the Bolivian government. To this day,
      Sucre remains the only official capital of Bolivia, but La Paz is considered by many as the de facto capital.
