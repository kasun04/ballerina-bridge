

Add Reservation 

`` curl -v -X POST -d '{"fullName":"Hotel_Marriot_Reserved!", "checkIn":"Hotel_Marriot_Reserved!", "checkOut":"Hotel_Marriot_Reserved!", "rooms":10001}' \
 "http://localhost:8080/reservation/hotel" -H "Content-Type:application/json" ``
 

Get All Reservations 

`` curl http://localhost:8080/reservation/hotel ``