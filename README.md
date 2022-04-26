# ljfdeering-Liam-Deering-LSBU-Specilaism-Edge-Dection-Shader



Edge Detection  

To set this up is a rather complex process. The first step in this is to pick the right piperline, for this we’ll pick URP.

Then you have to make sure to install the shader graph package 

Now from here you’ll have to find the “Universal Render Pipeline Asset_Render” and add a render feature and call it “DepthNormals” 

Note this should be the preexisting “Universal Render Pipeline Asset_Render” not the one included in the package

![Screenshot (9)](https://user-images.githubusercontent.com/91532021/165271037-ade205e1-dca5-4017-9009-e2aeb8814b63.png)

From here you add a new material and set the shader as shadergraph/simpleOutLines
There are a few main variables to keep in mind these are 
OutLinethickness:a good range is 0.001-0.003
OutlineAcuteStartDot: 0.9 
OutLineNomralStrength: 128
