## Cascade Layers CSS

#### Cascade Layers allow us to group together styles in different layers 

#### Than specificity rules only apply to selectors within same layer as eachouther

#### Any styles defined outside of layers have precedence over styles defined inside layers and the specificity of the selectors doesn't matter

#### Think of layers as a way to define a new scope within style sheet, where any selectors defined within the same layer have the same, kind of, local scope as each other 

#### The order of layers inside of style sheet matters 

#### We can define our layer order at the top of a styles sheet and then that will deternine the order of the layers within style sheet, and then the order of the layers defined below in the CSS doesn't matter

#### We can import 3rd party libraries and apply a layer to it