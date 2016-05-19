# saveSvgAsPngJpgSvg

Demo Here:              <a href="https://jsfiddle.net/akhilsahu/Ldqkqn45/">Click</a>

You can convert svg files to jpg ,Png and Svg file.This tool works effectively even if there are files included in the SVG.
Include the 
      
            svg.js file.

1.Add Html tags:
   
   Png Container 
   
               <div id="png-container"></div>
         
   Canvas Holder
   
               <p id="canvasHolder"></p>

2. Call
         
             genuri(type,idofSvg)

      Here type can be 
               svg ,png,jpg,pdf, print  (case sensitive)
      
         example:
      
         for png download call function and id of svg tag is svgid
   
         genuri('svg','svgid')

Note: Pdf is also possible if you include jspdf :https://github.com/MrRio/jsPDF
            Call function 
                  genuri('pdf','svgid')
