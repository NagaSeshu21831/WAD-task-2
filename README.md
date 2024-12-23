body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #f4f4f9; 
}

frame
 {
  border: none; 
}

frame[name="fr1"] {
  background-color: #1e1e2f; 
  color: #ffffff; 
}

frame[name="fr2"]
 {
  background-color: #2a2a3d; 
  color: #ffffff;

}

frame[name="fr3"],
frame[name="fr4"],
frame[name="fr5"],
frame[name="fr6"],
frame[name="fr7"] 
{
  background-color: #3d3d5c; 
  color: #ffffff; 
  font-weight: bold;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
}

frame[name="fr8"] 
{
  background-color: #2a2a3d;   
  color: #ffffff; 
  padding: 10px;
}


frame[name="fr9"]
 {
  background-color: #3d3d5c;
  color: #000000;
  padding: 10px;
}

frame[name="fr3"]:hover,
frame[name="fr4"]:hover,
frame[name="fr5"]:hover,
frame[name="fr6"]:hover,
frame[name="fr7"]:hover 
{
  background-color: #565678;
  cursor: pointer;
}
