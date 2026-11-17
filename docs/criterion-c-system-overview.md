## Flight Route Storage
- A database stores all airports
- Airports have a list of connections to other airports along with the transversal cost (distance, airplane type/efficiency) and schedule
- From a fictive customer app, customers request a route between two airports along with ticket price. Airline app does node transversal across the relevant airport nodes and returns the most favorable route (from the airport's perspective), along with timing constraint to not have layovers over x hours
- Ticket prices are determined by airline projected sales needed to turn a profit (?)

## Ticket Saving
- A database stores tickets by number, seat position, ticket holder, and connecting tickets
- When customer makes purchase, the ticket is added to airline's database
