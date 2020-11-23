# Final-Project/Data

The data was directly obtained from UCI machine learning database.

The code to obtain the data is:

Data <- read.table("http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data", sep=",", header=F, col.names=c("age", "type_employer", "fnlwgt", "education", "education_num", "marital", "occupation", "relationship", "race", "sex", "capital_gain", "capital_loss", "hr_per_week", "country", "income"), fill=FALSE, strip.white=T)