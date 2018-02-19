EE569 Homework Assignment 1
Date: 02/04/2018
Name: Apoorva Desai
ID: 5876264403
Email: apoorvad@usc.edu

IDE:Visual Studio
Description: Contains instructions on how to execute the following programs. You will find the respective input images in the same folder. Names of the output images can be changed.
//////////////////////////////////////////////////////////
Problem1:BasicImageManipulation(30%)

(a)ColorSpaceTransformation(Basic:18%)

1)Colour to Grayscale conversion
	
Greyscale by Average Method
	
	Filename:DIPHW1Aver.sln
	Commandline Arguments:Tiffany.raw Average.raw 
	
Greyscale by Lightness Method
	
	Filename:Lightness.sln
	Commandline Arguments:Tiffany.raw Lightness.raw 
	
Greyscale by Luminosity method
	
	Filename: DIPHW1Lum.sln
	Commandline Arguments:Tiffany.raw Lum.raw

2)CMY Colourspace

	Filename: CMYtrial2
	Commandline Arguments:Dance.raw DanceC.raw
	Instructions:Comment line 81-99 to generate greyscale for C.
	     	Comment line 71-81 and 91-101 to generate greyscale for M.
	     	Comment line 71-90 to generate greyscale for Y.

b)Image Resizing Using Bilinear Interpolation

	Filename:DIPHW1Scaling.sln
	Commandline Arguments:Airplane.raw AirplaneOP.raw
	Instructions: Height1=Height of smaller image
		      Width1= Width of Smaller image
		      Height2=Height of Larger Image
		      Width2=Width of Larger Image
////////////////////////////////////////////////////////////////////////////////
Problem 2 
a)Histogram equalization

Method A

Filename:DIPHW1Histeq.sln
	Commandline Arguments:Desk.raw DeskGrayReq.raw

Method B

Filename:DIPHW1Histeq2.sln
	Commandline Arguments:Desk.raw DeskMethB.raw
-------------------------------------------------------
b)Oil Painting Effect
For Star_Wars.raw
Filename:DIPHW1colorQuant.sln
	Commandline Arguments:Star_Wars.raw SWQuant2.raw
	Instructions: change values of variables from Line 29-31:
	const int Width = 600; //Width
	const int Height = 338;//Height
	const int radius = 1; //Radius of the NxN Oil painting filter to be applied. 1= 3x3, 2= 5x5, 3=7x7 etc.
	const int quant = 8; //Quantization factor. 4 gives 64 colours. 8 gives 512 colours.
Repeat for Trojans_720x480.raw
Filename:DIPHW1colorQuant.sln
	Commandline Arguments:Trojans_720x480.raw Toutput.raw
	Instructions: change values of variables from Line 29-31:
	const int Width = 720;//Width
	const int Height = 480;//Height
	const int radius = 1; //Radius of the NxN Oil painting filter to be applied. 1= 3x3, 2= 5x5, 3=7x7 etc.
	const int quant = 8; //Quantization factor. 4 gives 64 colours. 8 gives 512 colours.
-------------------------------------------------------
c)Image Filtering for Special Film effect

Filename:DIPHW1Film.sln
	Commandline Arguments:Girl.raw writeGirl.raw

////////////////////////////////////////////////////////////////////
Problem 3 Denoising
a) Mix Noise in colour Image

Filename:DIPHW1Film.sln
	Commandline Arguments:Lena_mixed.raw Lena.raw FilteredOutput.raw
	Instructions:change value of
		const int radius = 1; on line 59 to vary the radius of the Median and mean filter.////Radius of the NxN filter to be applied. 1= 3x3, 2= 5x5, 3=7x7 etc.
///////////////////////////////////////////////////////////////////




	

			
