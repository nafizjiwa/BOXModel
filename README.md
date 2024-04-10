# BOXModel
### Box Model and what it is.

##### The CSS Box Model is a layout mechanism that the web browser uses to render content organized by box shaped eleemnts. <br/>
##### Each element is made up of 4 areas: <br/>
![image](https://github.com/nafizjiwa/BOXModel/assets/56348190/3c261939-0bb7-4c09-9414-8b1ee4be2143)<br/>
![image](https://github.com/nafizjiwa/BOXModel/assets/56348190/c4901cf1-9131-465b-aff9-61b2ef711fc8)<br/>
#### Content Area<br/>
##### The area contains the actual content of an element, including text and images.<br/>

#### Margin Area<br/>
##### Border the margin areas of neighbouring elements.<br/>

##### All elements are in a box <br/>

```<div class="1">```<br/>
```  <div class="2"> </div>```<br/>
```  <div class="3"> </div>```<br/>
```</div>```<br/>
![image](https://github.com/nafizjiwa/BOXModel/assets/56348190/df29b37f-0197-47d7-9363-3152caadb300)

By default the width does not include: margin, padding and borders.<br/> 
The default CSS:<br/>
```element { ```<br/>
```box-sizing: content-box;```<br/>
```      } <br/>```

So to find the width of the whole element we must add the left and right margin, left and right padding and left and right borders.

To include the border and paddiing in the width use border box and not content-box as a value for the property box-sizing.<br/>
```elementName { ```<br/>
```box-sizing: border-box;```<br/>
```      } ```<br/>

###WIDTH = content width + padding + border 

#### Neighbours margins can collapse onto each other as below<br/>
![image](https://github.com/nafizjiwa/BOXModel/assets/56348190/892fd431-a51e-44ed-a74b-4fe5a0dd770f)










