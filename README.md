# Chapter 5 Key Idea
    convolution layers learn local patterns (pg.111)
    
    This key characteristic gives convnets two interesting properties:
    
    The patterns they learn are translation-invariant , i.e. after learning a certain pattern in the
    bottom right corner of a picture, a convnet is able to recognize it anywhere, e.g. in the top
    left corner. A densely-connected network would have to learn the pattern anew if it
    appeared at a new location. This makes convnets very data-efficient when processing
    images (since the visual world is fundamentally translation-invariant ): they need less
    training samples to learn representations that have generalization power.
    
    They can learn spatial hierarchies of patterns. A first convolution layer will
    learn small local patterns such as edges, but a second convolution layer will learn larger
    patterns made of the features of the first layers. And so on. This allows convnets to
    efficiently learn increasingly complex and abstract visual concepts (since the visual world
    is fundamentally spatially hierarchical ).
    
    A "response map" of the filter over the input, indicating the response of that filter
    pattern at different locations in the input (figure 5.3). That is what the term "feature map"
    really means: every dimension in depth axis is a feature (or filter), and the 2D tensor
    output[:, :, n] is the 2D spatial "map" of the response of this filter over the input.

    A deep neural network effectively acts as an information distillation pipeline, with raw data
    going in (in our case, RBG pictures), and getting repeatedly transformed so that
    irrelevant information gets filtered out (e.g. the specific visual appearance of the image)
    while useful information get magnified and refined (e.g. the class of the image). (pg.153)

# Chapter 6 Key Idea
    Deep learning for natural language processing is simply pattern
    recognition applied to words, sentences, and paragraphs, in much the same way that
    computer vision is simply pattern recognition applied to pixels.

# Chapter 8 Key Idea
    Artificial intelligence is
    not about replacing our own intelligence with something else, it is about bringing into our
    lives and work more intelligence, intelligence of a different kind.
    
    AI will be used by humans as a tool to augment their own
    capabilities: more augmented intelligence than artificial intelligence.
