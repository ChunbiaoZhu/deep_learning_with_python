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
    
    a "response map" of the filter over the input, indicating the response of that filter
    pattern at different locations in the input (figure 5.3). That is what the term "feature map"
    really means: every dimension in depth axis is a feature (or filter), and the 2D tensor
    output[:, :, n] is the 2D spatial "map" of the response of this filter over the input.
