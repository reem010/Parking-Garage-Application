# Project Details

<!DOCTYPE html>
<html>
<body>
  <h2>Application Description</h2>
  <p>Applying the Object-Oriented concepts (Abstraction, polymorphism, interfaces, packaging, ...) utilizing Boundary, control and entity concepts as well as SOLID Principles to design a Parking Garage application and implement it using an object-oriented programming language.</p>
  
  <h2>Functionality</h2>
  <ul>
    <li>Each vehicle shall be identified by a model name, unique identification number, Model year, and vehicle dimensions (vehicle width and depth).</li>
    <li>Park-in function that marks the arrival time of a vehicle if there is an available slot. The application shall capture such time automatically from the system.</li>
    <li>During the park-in function, the application shall pick a free slot based on the active slot configuration. There are two configurations:
      <ol type="i">
        <li>First come first served slots i.e., the park-in function will use the first free slot available from the parking garage slots.</li>
        <li>Best-fit approach where you need to find the slot with the minimum dimension to hold the vehicle.</li>
      </ol>
    </li>
    <li>Park-out function that marks the departure time of a vehicle from the garage. The application shall capture such time automatically from the system.</li>
    <li>Calculate the parking fees during the park-out based on the time-of-stay with an hourly rate of 5 EGP.</li>
    <li>Calculate the total income as well as the total number of vehicles that used the parking garage at any given point in time.</li>
    <li>Display the available parking slots.</li>
    <li>The application has the capability to handle a set of exceptions that can happen during user interaction and through any other calculations. The displayed error message for exceptional behavior should be descriptive.</li>
  </ul>
  
  <h2>Project Inclusions</h2>
  <ul>
    <li>A software requirements specification document.</li>
    <li>A software design specification document.</li>
    <li>The source for the Implementation of All features explained in the Project details section.</li>
    <li>A word document includes answering the following question:
      <ul>
        <li>Does your class diagram respect or violate SOLID principles? </li>
        <li>Does your class diagram contain any design pattern(s)? </li>
      </ul>
    </li>
  </ul>
</body>
</html>
