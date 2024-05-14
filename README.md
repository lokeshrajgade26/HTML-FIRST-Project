<!DOCTYPE html>
<html>
<head>
   
    <title>Form</title>
</head>
<body>
    <br/>
 <h1> Hotl booking  </h1>
 <hr>
 <br/> 
 <form>
     <label for="input full Name"> Enter Full Name:</label>
     <input type="text" id="input full Name" required="true" />

     <br/><br/>

     <label for="input birth Of Date"> birth Of Date:</label>
     <input type="date" id="input birth Of Date" required="true" />

      <br/><br/>

     <label for="input Full Address">Full Address:</label>
     <input type="text" id="input Full Address" required="true" />

      <br/><br/>

      <label for="input Nationality"> Nationality:</label>
      <input type="text" id="input Nationality" required="true" />

      <br/><br/>

      <label for="input  City/County"> City/County:</label>
      <input type="text" id="input City/County" required="true" />

      <br/><br/>

      <label for="input Email ID"> Email ID:</label>
      <input type="email" id="input Email ID" required="true" />
      
      <br/><br/>

      <label for="input phone "> phone:</label>
      <input type="number" id="input phone" required="true" />

      <br/><br/>

      Time: <input type="time" />

       <br/><br/>

      <label for="input  Male "> Male:</label>
      <input type="checkbox"  id="  Male" required="true"  />
      
      <br/><br/>

      <label for="input Number OF male "> Number OF male:</label>
      <input type="number" id="input Number OF male" required="true" /> 
       
      <br/><br/>

      <label for="input  Female "> Female:</label>
      <input type="checkbox" id=" Female" required="true"  />
       
      <br/><br/>

      <label for="input  Number OF Female"> Number OF Female:</label>
      <input type="number" id="input  Number OF Female" required="true" /> 
      
      <br/><br/>

      <label for="input  Number OF Room"> Number OF Room:</label>
      <input type="number" id="input  Number OF Room" required="true" /> 

      <br/><br/>

      <label for="input  AC ROOM "> AC ROOM:</label>
      <input type="checkbox" id=" AC ROOM " required="true"  /> <be/>

      <label for="input Cooler ROOM "> Cooler ROOM :</label>
      <input type="checkbox" id="Cooler ROOM" required="true"  />
       
      <label for="input  Normal ROOM "> Normal ROOM:</label>
      <input type="checkbox" id=" Normal ROOM" required="true"  />
       
      <br/><br/>

      <label for="selectLanguage">Choose BED :</label>  
      <select id="Choose BED">
        <option> Single BED </option>
        <option> double BED</option>
        <option>Three Single BEBS</option>
        <option>Two Single BEDS</option>
      </select>
       
      <br/><br/>

      <label for="fileInput"> Upload ID Proof Of Images</label>
      <input type="file" id="fileInput" accept="image/*" />

      <br/><br/>

      <input type="submit" value="book Now" />

 </form>
</body>
</html>
