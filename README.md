# cloudApp
## run
#### docker run -p 5000:5000 -it $(docker build -q .) 

//Summary : Separating sounds by using characteristics of the sound as a criterion for separation, such as similar tones. will be separated into 1st and 2nd, 3rd person voice, respectively, that the program will be able to detect.
     After separating the voice into individuals The program will change Speech to Text and store it in Document format to be a summary report in the meeting.
     From experiments, it is known that training data in a small number of times make the result of learning came out unclear a lot of mistakes It can be observed from the result that the separation of the number of speakers is not complete or exceeds the actual number of sounds that occur.
     At present, this research is not very widespread. make the research of this project It's still not 100% perfect, so there's no research that can prove that this project is feasible.
