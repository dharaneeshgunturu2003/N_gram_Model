Predicting is difficult—especially about the future, as the old quip goes. But how
about predicting something that seems much easier, like the next few words someone
is going to say? What word, for example, is likely to follow
Please turn your homework ...
Hopefully, most of you concluded that a very likely word is in, or possibly over,
but probably not refrigerator or the. In the following sections we will formalize
this intuition by introducing models that assign a probability to each possible next
word. The same models will also serve to assign a probability to an entire sentence.
Such a model, for example, could predict that the following sequence has a much
higher probability of appearing in a text:
all of a sudden I notice three guys standing on the sidewalk
than does this same set of words in a different order:
on guys all I of notice sidewalk three a sudden standing the
Why would you want to predict upcoming words, or assign probabilities to sentences? Probabilities are essential in any task in which we have to identify words in
noisy, ambiguous input, like speech recognition. For a speech recognizer to realize
