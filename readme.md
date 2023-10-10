
### CSharp-Keras-Integration

#### Introduction

- A base class library leveraging Keras & CSharp to implement deep learning models, specifically .H5.
- Easily deploy in any application environment.

#### Features

- Simple extraction of Keras models
- Agile development & quick deployment
- Code readability

#### Tutorial

A detailed tutorial is provided in this [video](https://www.bilibili.com/video/av93374622).

Some quick steps are provided below:

1. Put the .H5 model file in the Input folder (make sure it's a BP network or CNN structure), run model_analysis.py file, press Enter, and your weight file will appear in the Output folder.

2. Place class library files in the root directory of the program.

3. Import Wineforever.Neuralnet.dll and reference namespace:
   ```c#
   using Wineforever.Neuralnet;
   ```

4. Create a neural network System:
   ```c#
   var sys = new Wineforever.Neuralnet.System('sys');
   ```

5. Create Layers, ensuring model structure consistency:
   ```c#
   //Sample code for BP net and CNN given
   ```

6. Load Weights.

7. Set Input.

8. Make Predictions.

#### Updates

Version 2.0 marked a significant improvement in the speed of forward propagation. Various updates have been made in each version, focusing on increasing efficiency and making the class library more lightweight.

#### Agreement

This class library adheres to open-source protocols and is purely for non-commercial use.

#### Donate

We welcome and appreciate your support. Donations can be made via the provided QR code or Bitcoin Wallet (16RpsEY6C1zLZTPZUX8mXK9ozooqhh5YqS).

![](http://106.15.93.194/donate/donate.png)