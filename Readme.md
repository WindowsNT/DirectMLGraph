# DirectML Graph

A tool to visually-design DirectML operators that run in the GPU.
Uses my [DirectML Lib](https://github.com/WindowsNT/directmllib).

## Features

Undo, Redo, Save, Load, Multiple Sets

Multiple Visible/Active DirectML operators

Direct2D Drawing

Memory Sharing

Input/Output CSV or binary, Input Random, Output to MessageBox

Adapter Selection

Show Adapter Memory Consumed

## Supported Operators

Activation: Celu,Elu,Gelu,HardMax,HardSigmoid,Identity,LeakyRelu,Linear,LogSoftmax,ParameterizedRelu,ParametricSoftplus,Relu,ScaledElu,ScaledTanh,Shrink,Sigmoid,Softmax,Softplus,Softsign,Tanh,ThresholdedRelu

Batch Processing: BatchNormalization, BatchNormalizationGrad, BatchNormalizationTraining, BatchNormalizationTrainingGrad

Comparison Operators: If, IsInfinity, IsNaN

A: Abs,ACos,ACosh,Add,And,ASin,ASinh,ATan,ATanh,ATanYX,AveragePooling

B: BitAnd, BitCount, BitOr, BitNot, BitShiftLeft, BitShiftRight, BitXor

C: Cast, Ceil, Clip, ClipGrad, Constant, Cos, Cosh, Cummulative Sum/Product, Convolution

D: DepthToSpace, Dequantize, DequantizeLinear, DifferenceSquare, Divide

E: Erf, Exp, Equals

F: Floor

G: Gemm, GreaterThan, GreaterThanOrEqual

I: Identity, 

J: Join

L: Log, LessThan, LessThanOrEqual

M: Max,Mean,Min,Multiply,Modulus Floor,Modulus Truncate

N: Neg, Not

O: Or

P: Pow

R: Recip, Reduce, Resample, Round, Reintrerpret

S: Slice, Subtract, Sqrt, Sign

T: Threshold

X: Xor

### Pending

All other operators: 

                        dml::ConvolutionInteger;
                        dml::Gather;
                        dml::GatherElements;
                        dml::GatherND;
                        dml::LocalResponseNormalization;
                        dml::MaxPooling;
                        dml::MeanVarianceNormalization;
                        dml::NonZeroCoordinates;
                        dml::OneHot;
                        dml::Padding;
                        dml::QuantizedLinearConvolution;
                        dml::QuantizeLinear;
                        dml::RandomGenerator;
                        dml::ResampleGrad;
                        dml::ReverseSubsequences;
                        dml::RoiAlign;
                        dml::RoiAlignGrad;
                        dml::ScatterElements;
                        dml::SliceGrad;
                        dml::SpaceToDepth;
                        dml::TopK;
                        dml::Upsample2D;
                        dml::ValueScale2D;


![screenshot](graph1.jpg)