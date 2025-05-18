what deep learning is not good for 


when you need interpretability, ML or deep learning are typically uninterpretable by a human  considering there a lots of weights and biases 
whwn the traditional approach is a better option
when errors are unacceptable
when you dont have much data 


Algorithm:Gradient Boosted Machine XGBoost an ML for structured data 
Random Forrest
Naive Bayes
Nearest neighbour
support vector machines

use Deep learning for unstructured data --- these are neural networks based 
egs: Neural networks
fully conected neural network
convolutional neural network ------ for learning an image kind of input 
Recurrent neural netwok
Transformer ---- for a speach recognition kind of problem 

How do I learn ML
learn python 
learn Maths/Stats/Probaility
learn software engineering 
Build


practical demonstration

numerical encoding: turn your inputs(images) into numbers or matrixes and vectors or tensors  -->> pass the numbers into a neural networ ( this will extract patterns/features/weights or learn the represemtations) --->> this are called outputs(or learned representations or features)


different kinds of learning or learning paradigms
supervised learning 
unsupervised & self supervised learning 
Transfer learning 
reinenforced learning 

Deep learning apllications
recommendation systems 
tranlations
speech recognition
computer vision
images recognition 
natural language processing ( basically finding patterns in unstructtured texts or tweets or social media posts)


classifications
can be a regression based or sequence to sequence

how to represent data as a matrix:
{
        "daily_log": [["2024-o5-01", 50],
                    ["2024-o5-02", 40],
                    ["2024-o5-03", 60]
        ]
}

representing data as a Tensor:
{
    "user_data": [
        [[1, 0.3], [0, 0.7]],
        [[1, 0.3], [0, 0.3]],
        [[0, 0.3], [1, 0.4]]



    ]


}


How neural networks works

start with random numbers -->> look at data -->> update randome numbers -->> update random numbers