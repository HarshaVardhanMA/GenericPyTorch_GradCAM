## Generic Implementation of GradCAM which works on any style of building the PyTorch model.

Unlike many open-sourced implementations of GradCAM in PyTorch, which assumes a particular class architecture of a model (usually that of AlexNet or Inception or ResNet), this work here works with any PyTorch model.

Just remember to use the name of the layer(s) at which you want visualise, as it would appear in the model.named_modules().

Check the egs directory in the repo to find out more about using the GradCam class.
