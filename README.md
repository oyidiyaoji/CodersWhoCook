# CodersWhoCook
CodersWhoCook is a project I helped to develop for the Tech Together HobbyHacks Hackathon. The idea was to create a place to connect coders virtually and reduce the possible awkwardness of meeting new people via the magic of cooking. We wanted them to connect based on their language programming skills and the cuisines they like so for this we wanted to used machine learning. 

In order to build a model to match our users we created a a dataset. After doing an exploratory data analysis I encoded our categorical variables. I used ordinal encoder method to transform our data into numerical variables and used unsupervised machine learning techniques. Basically I clustered using Kmodes which is a clustering method suitable for categorical values. I finished clustering our users in 2 groups and I sorted them. The idea was to link users based on correlation. The users having a higher correlation with user 'A' will be the ones that will be shown to him/her. 
