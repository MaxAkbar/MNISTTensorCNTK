# MNIST Sample with Tensor<T> and CNTK
  
This sample is a very simple WPF application which recognizes hand-written digits using the pre-built MNIST convolutional model. The MNIST is Machine Learning's Hello World program. 

MNIST is a simple computer vision dataset which consists of hand written digits like as shown below. 

<img src="https://msdnshared.blob.core.windows.net/media/2017/11/Tensor.png"
     alt="Tensor<T> and CNTK"
     style="float: left; margin-right: 10px;" />

This tutorial comes with a pre-built CNTK model which is trained to look at these hand-written digits and predict what these digits are. We in this very first touch, dip a toe session with Machine Learning will consume that pre-built CNTK model into a .NET application that you are already used to. Follow the steps below to get going. 

Get Started 
1. If you are new to .NET, go ahead and download [Visual Studio 2017](https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15)
2. Clone this github repo using git clone. 

The sample consits of two projects in the solution 'Digitz' (C# project using Tensor<T> and CNTK pre-built MNIST model) and 'Training' (Python project, which generates the MNIST model). 

The sample provides you an example of how you can use Tensor<T> today with CNTK for using a pre-built CNTK MNIST model. To use this sample just clone this repo and launch it in Visual Studio 2017.

[Tensor<T>](https://blogs.msdn.microsoft.com/dotnet/2017/11/15/introducing-tensor-for-machine-learning-and-ai-libraries) is an exchange type for homogenous multi-dimensional data for 1 to N dimensions. The motivation behind introducing Tensor<T> is to make it easy for Machine Learning library vendors like CNTK, Tensorflow, Caffe, Scikit-Learn to port their libraries over to .NET with minimal dependencies in place.  Tensor<T> is designed to provide the following characteristics.

To learn more about [Tensor<T> follow our blog post](https://blogs.msdn.microsoft.com/dotnet/2017/11/15/introducing-tensor-for-machine-learning-and-ai-libraries) and [GitHub repo](https://github.com/dotnet/corefxlab/tree/master/src/System.Numerics.Tensors). 
  
To follow a video tutorial on this app being used you can also follow this video. 
https://channel9.msdn.com/Events/Connect/2017/t126


  
  
  
  



