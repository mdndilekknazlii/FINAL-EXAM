# FINAL-EXAM
#Create 2 matrices in the form of 2x3 for 2 different test results obtained at the same temperature. Print each of these experiment results as output in R using the for loop.
#Define your first matrix
experiment1<- matrix(c(25,30,35,300,200,100), nrow = 2, ncol = 3 , byrow = TRUE)
print(experiment1) 
#To print your result
for(i in 1:ncol(experiment1))
print(paste("For Experiment 1 the Temperature is :", experiment1[1,i] , "and the result is" , experiment1[2,i]))
#Define your second matrix
experiment2<- matrix(c(25,30))
experiment2<- matrix(c(25,30,35,250,150,50), nrow = 2, ncol = 3 , byrow = TRUE)
print(experiment2)
for(r in 1:ncol(experiment2))
  print(paste("For Experiment 2 the Temperature is :", experiment2[1,r] , "and the result is" , experiment2[2,r]))
