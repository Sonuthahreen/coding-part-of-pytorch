# coding-part-of-pytorch
In this introductory tutorial on tensors using PyTorch, several key concepts and operations were covered. Here's a summary along with some additional notes:

1. **Scalars, Vectors, Matrices, and Tensors**:
   - Scalars are single numbers, represented as zero-dimensional tensors.
   - Vectors are one-dimensional arrays of numbers.
   - Matrices are two-dimensional arrays of numbers.
   - Tensors are n-dimensional arrays of numbers, encompassing scalars, vectors, and matrices as special cases.

2. **Creation of Tensors**:
   - Tensors can be created using `torch.tensor()` function, with specified values or randomly initialized.
   - Dimensionality and shape of tensors can be determined using `.ndim` and `.shape` attributes respectively.
   - Scalars and vectors are commonly represented with lowercase letters, while matrices and tensors with uppercase letters.

3. **Random Tensors**:
   - Random tensors are often used in machine learning for initialization purposes.
   - `torch.rand()` generates random tensors with values from a uniform distribution between 0 and 1.

4. **Zeros and Ones**:
   - `torch.zeros()` and `torch.ones()` create tensors filled with zeros and ones respectively.
   - These functions take a `size` parameter to specify the shape of the tensor.

5. **Creating a Range and Tensors Like**:
   - `torch.arange()` generates a tensor containing values within a specified range with a given step size.
   - `torch.zeros_like()` and `torch.ones_like()` create tensors filled with zeros and ones, with the same shape as a specified input tensor.

6. **Tensor Datatypes**:
   - PyTorch supports various datatypes for tensors, including floating-point (e.g., `torch.float32`, `torch.float16`) and integer types.
   - Datatype can be specified using the `dtype` parameter when creating tensors.

7. **Device Compatibility**:
   - Tensors can be allocated on different devices, such as CPU or GPU.
   - PyTorch prefers tensors to have the same datatype and reside on the same device for efficient computation.
