# Breast_AI_tool

## system reqirement  
version of MATLAB Runtime: R2016a  
OS: Windows 10 or later

## user manual
![image](https://user-images.githubusercontent.com/11002888/212855907-66bad2a3-0b61-47fe-92ab-cd7060b1c1d7.jpg)

## input data format
![image](https://user-images.githubusercontent.com/11002888/212857053-4b7631cd-562f-46a3-826b-bdc9744d84b1.png)
## output data explanation

<html xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:x="urn:schemas-microsoft-com:office:excel"
xmlns="http://www.w3.org/TR/REC-html40">

<head>

<meta name=ProgId content=Excel.Sheet>
<meta name=Generator content="Microsoft Excel 15">
<link id=Main-File rel=Main-File
href="file:///C:/Users/masak/AppData/Local/Temp/msohtmlclip1/01/clip.htm">
<link rel=File-List
href="file:///C:/Users/masak/AppData/Local/Temp/msohtmlclip1/01/clip_filelist.xml">
<style>
<!--table
	{mso-displayed-decimal-separator:"\.";
	mso-displayed-thousand-separator:"\,";}
@page
	{margin:.75in .7in .75in .7in;
	mso-header-margin:.3in;
	mso-footer-margin:.3in;}
.font5
	{color:windowtext;
	font-size:6.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;}
tr
	{mso-height-source:auto;
	mso-ruby-visibility:none;}
col
	{mso-width-source:auto;
	mso-ruby-visibility:none;}
br
	{mso-data-placement:same-cell;}
td
	{padding-top:1px;
	padding-right:1px;
	padding-left:1px;
	mso-ignore:padding;
	color:black;
	font-size:11.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;
	mso-number-format:General;
	text-align:general;
	vertical-align:middle;
	border:none;
	mso-background-source:auto;
	mso-pattern:auto;
	mso-protection:locked visible;
	white-space:nowrap;
	mso-rotate:0;}
.xl66
	{font-size:9.0pt;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;
	text-align:center;}
.xl67
	{font-size:9.0pt;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;}
.xl68
	{font-size:9.0pt;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;
	border:.5pt solid windowtext;
	white-space:normal;}
.xl69
	{color:#0070C0;
	font-size:9.0pt;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;
	border:.5pt solid windowtext;}
.xl70
	{font-size:9.0pt;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;
	border:.5pt solid windowtext;
	white-space:normal;}
.xl71
	{color:red;
	font-size:9.0pt;
	font-weight:700;
	font-family:"Times New Roman", serif;
	mso-font-charset:0;}
ruby
	{ruby-align:left;}
rt
	{color:windowtext;
	font-size:6.0pt;
	font-weight:400;
	font-style:normal;
	text-decoration:none;
	font-family:游ゴシック, monospace;
	mso-font-charset:128;
	mso-char-type:katakana;
	display:none;}
-->
</style>
</head>

<body link="#0563C1" vlink="#954F72">



  | Input file CSV format
-- | --
Column No |  
1 | Case number of input file ;    Add for CellProfiler outputted file
2 | Slide number of input file ;  Add for CellProfiler outputted file
3 | Image Number of slides  ;    Add for CellProfiler outputted file
4 | ImageNumber   INTEGER
5 | ,ObjectNumber   INTEGER,
6 | Nuclei_Number_Object_Number   integer,
7 | Nuclei_AreaShape_Area   float,
8 | Nuclei_AreaShape_Center_X   float,
9 | Nuclei_AreaShape_Center_Y   float,
10 | Nuclei_AreaShape_Compactness   float,
11 | Nuclei_AreaShape_Eccentricity   float,
12 | Nuclei_AreaShape_EulerNumber   float,
13 | Nuclei_AreaShape_Extent   float,
14 | Nuclei_AreaShape_FormFactor   float,
15 | Nuclei_AreaShape_MajorAxisLength   float,
16 | Nuclei_AreaShape_MaxFeretDiameter   float,
17 | Nuclei_AreaShape_MaximumRadius   float,
18 | Nuclei_AreaShape_MeanRadius   float,
19 | Nuclei_AreaShape_MedianRadius   float,
20 | Nuclei_AreaShape_MinFeretDiameter   float,
21 | Nuclei_AreaShape_MinorAxisLength   float,
22 | Nuclei_AreaShape_Orientation   float,
23 | Nuclei_AreaShape_Perimeter   float,
24 | Nuclei_AreaShape_Solidity   float,
25 | Nuclei_Location_Center_X   float,
26 | Nuclei_Location_Center_Y   float,
27 | Nuclei_RadialDistribution_FracAtD_Gray_image_1of4   float,
28 | Nuclei_RadialDistribution_FracAtD_Gray_image_2of4   float,
29 | Nuclei_RadialDistribution_FracAtD_Gray_image_3of4   float,
30 | Nuclei_RadialDistribution_FracAtD_Gray_image_4of4   float,
31 | Nuclei_RadialDistribution_MeanFrac_Gray_image_1of4   float,
32 | Nuclei_RadialDistribution_MeanFrac_Gray_image_2of4   float,
33 | Nuclei_RadialDistribution_MeanFrac_Gray_image_3of4   float,
34 | Nuclei_RadialDistribution_MeanFrac_Gray_image_4of4   float,
35 | Nuclei_RadialDistribution_RadialCV_Gray_image_1of4   float,
36 | Nuclei_RadialDistribution_RadialCV_Gray_image_2of4   float,
37 | Nuclei_RadialDistribution_RadialCV_Gray_image_3of4   float,
38 | Nuclei_RadialDistribution_RadialCV_Gray_image_4of4   float,
39 | Nuclei_Texture_AngularSecondMoment_Gray_image_1_0   float,
40 | Nuclei_Texture_AngularSecondMoment_Gray_image_1_135   float,
41 | Nuclei_Texture_AngularSecondMoment_Gray_image_1_45   float,
42 | Nuclei_Texture_AngularSecondMoment_Gray_image_1_90   float,
43 | Nuclei_Texture_Contrast_Gray_image_1_0   float,
44 | Nuclei_Texture_Contrast_Gray_image_1_135   float,
45 | Nuclei_Texture_Contrast_Gray_image_1_45   float,
46 | Nuclei_Texture_Contrast_Gray_image_1_90   float,
47 | Nuclei_Texture_Correlation_Gray_image_1_0   float,
48 | Nuclei_Texture_Correlation_Gray_image_1_135   float,
49 | Nuclei_Texture_Correlation_Gray_image_1_45   float,
50 | Nuclei_Texture_Correlation_Gray_image_1_90   float,
51 | Nuclei_Texture_DifferenceEntropy_Gray_image_1_0   float,
52 | Nuclei_Texture_DifferenceEntropy_Gray_image_1_135   float,
53 | Nuclei_Texture_DifferenceEntropy_Gray_image_1_45   float,
54 | Nuclei_Texture_DifferenceEntropy_Gray_image_1_90   float,
55 | Nuclei_Texture_DifferenceVariance_Gray_image_1_0   float,
56 | Nuclei_Texture_DifferenceVariance_Gray_image_1_135   float,
57 | Nuclei_Texture_DifferenceVariance_Gray_image_1_45   float,
58 | Nuclei_Texture_DifferenceVariance_Gray_image_1_90   float,
59 | Nuclei_Texture_Entropy_Gray_image_1_0   float,
60 | Nuclei_Texture_Entropy_Gray_image_1_135   float,
61 | Nuclei_Texture_Entropy_Gray_image_1_45   float,
62 | Nuclei_Texture_Entropy_Gray_image_1_90   float,
63 | Nuclei_Texture_InfoMeas1_Gray_image_1_0   float,
64 | Nuclei_Texture_InfoMeas1_Gray_image_1_135   float,
65 | Nuclei_Texture_InfoMeas1_Gray_image_1_45   float,
66 | Nuclei_Texture_InfoMeas1_Gray_image_1_90   float,
67 | Nuclei_Texture_InfoMeas2_Gray_image_1_0   float,
68 | Nuclei_Texture_InfoMeas2_Gray_image_1_135   float,
69 | Nuclei_Texture_InfoMeas2_Gray_image_1_45   float,
70 | Nuclei_Texture_InfoMeas2_Gray_image_1_90   float,
71 | Nuclei_Texture_InverseDifferenceMoment_Gray_image_1_0   float,
72 | Nuclei_Texture_InverseDifferenceMoment_Gray_image_1_135   float,
73 | Nuclei_Texture_InverseDifferenceMoment_Gray_image_1_45   float,
74 | Nuclei_Texture_InverseDifferenceMoment_Gray_image_1_90   float,
75 | Nuclei_Texture_SumAverage_Gray_image_1_0   float,
76 | Nuclei_Texture_SumAverage_Gray_image_1_135   float,
77 | Nuclei_Texture_SumAverage_Gray_image_1_45   float,
78 | Nuclei_Texture_SumAverage_Gray_image_1_90   float,
79 | Nuclei_Texture_SumEntropy_Gray_image_1_0   float,
80 | Nuclei_Texture_SumEntropy_Gray_image_1_135   float,
81 | Nuclei_Texture_SumEntropy_Gray_image_1_45   float,
82 | Nuclei_Texture_SumEntropy_Gray_image_1_90   float,
83 | Nuclei_Texture_SumVariance_Gray_image_1_0   float,
84 | Nuclei_Texture_SumVariance_Gray_image_1_135   float,
85 | Nuclei_Texture_SumVariance_Gray_image_1_45   float,
86 | Nuclei_Texture_SumVariance_Gray_image_1_90   float,
87 | Nuclei_Texture_Variance_Gray_image_1_0   float,
88 | Nuclei_Texture_Variance_Gray_image_1_135   float,
89 | Nuclei_Texture_Variance_Gray_image_1_45   float,
90 | Nuclei_Texture_Variance_Gray_image_1_90   float,



</body>

</html>
