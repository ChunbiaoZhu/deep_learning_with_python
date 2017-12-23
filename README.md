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
  
# Summary  
    anything that requires reasoning—like
    programming, or applying the scientific method—long-term planning, and
    algorithmic-like data manipulation, is out of reach for deep learning models, no matter
    how much data you throw at them. Even learning a sorting algorithm with a deep neural
    network is tremendously difficult.
    
    All it can do is map
    one data manifold X into another manifold Y, assuming the existence of a learnable
    continuous transform from X to Y. So even though a deep learning model can be
    interpreted as a kind of program, inversely most programs cannot be expressed as deep
    learning models—for most tasks, either there exists no corresponding deep neural
    network that solves the task, or even if there exists one, it may not be learnable, i.e. the
    corresponding geometric transform may be far too complex, or there may not be
    appropriate data available to learn it.
    
    In short, deep learning models do not have any understanding of their input, at least
    not in any human sense. Our own understanding of images, sounds, and language, is
    grounded in our sensorimotor experience as humans. Machine learning models have no
    access to such experiences and thus cannot "understand" their inputs in any
    human-relatable way. By annotating large numbers of training examples to feed into our
    models, we get them to learn a geometric transform that maps data to human concepts on
    this specific set of examples, but this mapping is just a simplistic sketch of the original
    model in our minds, the one developed from our experience as embodied agents—it is
    like a dim image in a mirror.
    
    In short, deep learning models do not have any understanding of their input, at least
    not in any human sense. Our own understanding of images, sounds, and language, is
    grounded in our sensorimotor experience as humans. Machine learning models have no
    access to such experiences and thus cannot "understand" their inputs in any
    human-relatable way. By annotating large numbers of training examples to feed into our
    models, we get them to learn a geometric transform that maps data to human concepts on
    this specific set of examples, but this mapping is just a simplistic sketch of the original
    model in our minds, the one developed from our experience as embodied agents—it is
    like a dim image in a mirror.
