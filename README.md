mydata<- read.csv("outcome-of-care-measures.csv", colClasses = "character")
# head(outcome)
names(outcome)
mydata[, 11] <- as.numeric(mydata[, 11])  
