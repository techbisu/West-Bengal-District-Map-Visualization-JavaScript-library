# West-Bengal-District-Map-Visualization-JavaScript-library
West Bengal District Map Visualization JavaScript library easy ways of displaying statistical data on maps

<img src="https://github.com/techbisu/West-Bengal-District-Map-Visualization-JavaScript-library/raw/main/wbmapview.png"/>

# Step-1
  download wbmap.min.js & wbsvg.svg 
  
  then upload this 2 file in your project js folder & include the wbmap.min.js in your html body
  
  like this
  
  <code><script type="text/javascript" src="yoururl/wbmap.min.js"></script></code>
  
  change the src as per your project location
  
  #Step 2
  
  add 1 div with id="wbmapview" inside your html section where you want to show map
  
  <code>id="wbmapview"</code>
  
  #Step 3
  
  now call a javascript function & pass your data
  
  <code><script type="text/javascript">




    var dist = ["Darjeeling", "Jalpaiguri", "Cooch Behar", "Uttar Dinajpur", "Dakshin Dinajpur", "Maldah", "Murshidabad", "Birbhum", "","Nadia", "North 24 Parganas","Hooghly", "Bankura", "Purulia", "Paschim Medinipur", "Howrah", "Kolkata", "South 24 Parganas", "Purba Medinipur", "Alipurduar", "Kalimpong","Paschim Bardhaman", "Purba Bardhaman", "Jhargram"];

    var total = ["987200", "221900", "121900", "123900", "103900", "113400", "913400", "513400", "713400", "119400","213400", "193400", "893400", "456400", "312400", "993400", "112289", "113892", "823400", "129000","673400", "178400", "113499", "113788"];

    var sc = ["3219", "22190", "1210", "1200", "1039", "1400", "9130", "5130", "7134", "9400","2130", "1930", "8930", "4560", "3120", "9400", "1129", "1892", "82300", "1290","6730", "1700", "1499", "3788"];

    var st = ["3210", "2200", "1900", "1400", "1039", "1134", "9130", "5190", "7400", "1190","2400", "3400", "8934", "4560", "3400", "9930", "1289", "1892", "3400", "1290","6730", "1780", "1499", "3788"];

    var obc = ["3219", "2210", "1210", "1900", "3900", "1130", "9130", "5130", "713400", "1190","2130", "1400", "890", "4564", "3120", "9400", "1129", "1192", "800", "1290","6730", "8400", "3499", "1138"];

    wbmap(dist,total,sc,st,obc);

    
    
</script></code>


like this ...

must follow the same district list serial which we done


let's enjoy..
