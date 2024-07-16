# project4_metacrafter

# Hotel Room Booking Smart Contract

This Solidity smart contract manages the booking of hotel rooms on the blockchain. It allows users to book available rooms and check their status.

## Features

- **Room Booking:** Users can book available rooms.
- **Room Status Check:** Users can check the status of any room.
- **Occupant Retrieval:** Get the occupant address of a room.

### Example

```solidity
// Deploy the contract
HotelRoomBooking roomBooking = new HotelRoomBooking(10);

// Book a room
roomBooking.bookRoom(1);

// Check room status
RoomStatus status = roomBooking.checkRoomStatus(1);

// Get room occupant
address occupant = roomBooking.getRoomOccupant(1);
```

### License

This project is licensed under the MIT License .

### Acknowledgments

- Solidity documentation
- Ethereum community

