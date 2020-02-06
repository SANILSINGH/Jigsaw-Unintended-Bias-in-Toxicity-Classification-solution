<h2>1. Business problem:</h2>

The objective was to detect toxic comments and reduce the unintended bias of the model.

### Problem Description

The Conversation AI team (it is research initiated by Jigsaw and Google) build a toxicity model, they found that the model incorrectly learned to associate the names of frequently attacked identities with toxicity. So the model predicted high toxicity for those comments which contain words like gay, black, Muslim, white, lesbian, etc, even when comments were not actually toxic (e.g. I am a gay woman.). This happened because the dataset was collected from the sources where such words (or identities) are considered as highly offensive. A model is needed to be build which can find the toxicity in the comments and minimize the unintended bias with respect to some identities.

1. A toxic comment is that comments which are offensive and sometimes they make some people leave the discussion (on public forums).
    
2. unintended bias is related to unplanned bias which happened because the data was collected from such sources which considered some words (or identities) very offensive.

### Background info

When the Conversation AI team first built toxicity models, they found that the models incorrectly learned to associate the names of frequently attacked identities with toxicity. Models predicted a high likelihood of toxicity for comments containing those identities (e.g. “gay”), even when those comments were not actually toxic (such as “I am a gay woman”). This happens because training data was pulled from available sources where, unfortunately, certain identities are overwhelmingly referred to in offensive ways. Training a model from data with these imbalances risks simply mirroring those biases back to users.

So we have to build a model that recognizes toxicity and minimizes this type of unintended bias with respect to mentions of identities.

### Problem Statement

The model which was built by The Conversation AI team has the problem of unintended bias and this has to be removed (or minimized) because of this the comments which are not actually toxic will be predicted as toxic and this is not good for our business.
