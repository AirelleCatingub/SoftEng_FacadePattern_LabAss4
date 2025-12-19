# SoftEng_FacadePattern_LabAss4
Simplified Hotel Management System

## Problem Statement
The HotelApp needs to manage various hotel services for guest check-in and check-out. These services include valet parking for vehicles, room cleaning, and handling luggage carts. However, the HotelApp aims to interact with these services through a simplified, single interface provided by the FrontDesk. The FrontDesk class should delegate the client's requests to the appropriate service classes (Valet, HouseKeeping, Cart) while abstracting the service details from the client.

<h2><strong>Class Definitions:</strong></h2>
<ul>
  <li><strong>HotelService (Interface): </strong> – Defines the common interface for all hotel services.</li>
  <li><strong>Valet:</strong> – A service class implementing the HotelService interface, responsible for vehicle valet parking and pick-up. It includes the pickUpVehicle(plateNumber) method.</li>
  <li><strong>HouseKeeping:</strong> – A service class implementing the HotelService interface, responsible for room cleaning. It includes the cleanRoom(roomNumber) method.</li>
    <li><strong>Cart:</strong> – A service class implementing the HotelService interface, responsible for handling luggage cart requests. It includes the requestCart(numberOfCarts) method.</li>
  <li><strong>FrontDesk:</strong> – The facade class that coordinates interactions between the client (HotelApp) and the individual hotel services.</li>
  <li><strong>HotelApp: </strong> – The client class that uses the FrontDesk facade to access and utilize hotel services seamlessly.</li>
</ul>
