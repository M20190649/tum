### Public Transportation
* Modes
  * Bus
    * BRT
      * may allow stopping of two buses, overtaking lanes
  * Light Rail
    *  wide range of systems, unidirectional or bidirectional, low floor, tram-trains
    * Streetcar
    * Tram
    * Light Rail
  * Heavy Rail
    * Subway / Metro (Rail Rapid Transit, Light Rail Rapid Transit, Rubber-tired Rapid Transit)
    * Regional Rail
    * Monorail
  * Automated Guided Transit
* Characteristics
  * Right-of-way
    * A: Dedicated ways and intersections
      * heavy rail
      * high investment cost, performance (speed, reliability, capacity), low operating cost/passenger, high frequencies
      * large distance between stops, sparce network
      * stations as placemaking w/ information, off-vehicle fare collection
      * simple network, map, convenient transfers, many doors
    * B: Dedicated ways and shared intersections
      * lrt, brt, bus lanes
      * mid costs and performance
      * stations as placemaking w/ information, off-vehicle fare collection, medium stop spacing
      * simple network, map, convenient transfers, many doors
      * intersection prioritization, traffic control center
    * C: Shared ways and intersetions
      * buses, trolley buses, streetcars, trams
      * good accessibility, short distance between stops, dense network
      * low-mid cost investment cost
      * low speed, performance depends on traffic conditions, slower than private cars
      * complex networks, no maps
  * Vehicle Guidance
    * Track / Guideway
      * allows for longer vehicles (higher capacity), less land use, better for tunnels, safety/automation possible
      * higher cost, higher stop spacing, less flexibility
    * Driver Steered
  * Propulsion
    * Dinosaurs: Diesel, CNG, LNG
    * Electric
      * higher acceleration, regenerative braking, no local pollution
      * higher investment cost, less reliable
    * Hybrid
  * Control
    * Driver
    * Automatic Train Operation
      * lowest headways, higher cost
      * w/ Driver
      * w/o Driver
        * lower cost
* Line Length
  * Long: more direct trips, more efficient (less down time)
  * Short: less delay propagation, difficult run cutting
* Interconnections
  * Integrated
    * more direct trips/options, can schedule to match passenger demand, rerouting possible
    * more complex
    * common for bus networks
  * Independent
    * greater overall capacity, less delay propegation, less complex
    * common for large networks in big cities
* Lines
  * Radial
    * one terminal in city, one in suburbs
    * service follows demand direction, unbalanced demand
    * decreasing passenger volume outward from city
      * can run short lines from city
      * can branch
    * poor connectivity, terminals in city = poor use of space
    * w/ Loop
  * Diametrical
    * radial, but through city
    * balance demand on both sides, unbalanced demand city to suburb
    * better connectivity than radial, better use of space
    * delay propegation
    * L-shape = better connectivity, more direct trips
    * U-shape: balance demand between lines
  * Tangential
    * typically low demand
  * Circle
    * great for connectivity, suburb to suburb
    * vulnerable to delay propegation, headway must be integer fraction of the cycle time
      * open the circle
      * go slower than maximum possible -> speed up when delayed
      * stop at station w/ most transfers, fewest through passengers
    * Loop e.g. Singapore LRT
  * Trunk
    * solves demand problem
    * rail2rail: requires coordination of schedules, infrastructure, better passenger experience
    * w/ Branches
      * direct, longer lines
    * rail2road: cheaper/easier
    * w/ Feeder
      * no delay propagation, can use different modes
* Networks
  * Radial
    * service follows demand direction, unbalanced demand, high passenger value
    * few transfers (not possible)
  * Radial/Cicumfrential
    * suburb2suburb, better connectivity
  * Grid
    * good connectivity, lots of transfers
    * useful for all trip types
  * Ubiquitous
    * many direct trips, lots of connectivity
    * useful for all trip types
  * Irregular
    * service follows geography
* Integration (Transfers)
  * No Transfers: Commuter or Highly Integrated 
  * Transfers: High Capacity Independent Lines
    * Hierarchical Structure: Functions: keep seperate
      * Collection/distribution - accessible, e.g. bus
      * Long-distance transport - fast, e.g. rail
    * perceived travel time with transfers must be less than perceived travel time w/ direct service
  * Requirements
    * Network Design / Transfer Stations
      * e.g. Timed-transfer Stations
    * Schedule Coordination
      * uniform headway - easy to remember, balanced passenger loads -> less bunching
      * timed transfers: arrive together, wait a bit, depart together
      * short2short: no problem
      * long2short: no problem
      * short2long: publish timetable
      * long2long: same headway: timed transfer or only-one way transfers (one arrives and departs before the other), different headway: problem
      * 3 Situations at a Terminal
        * All lines terminate -> Timed-transfers
	* Some terminate, some through -> middle case
	* All lines through -> Maybe timed-transfer, if lots of transfers, but delays though passengers
    * Integrated Ticketing
    * Good Passenger Information
    * Traffic Control Center
      * incident management, passenger information, signal prioritization
* Fares
  * Goals: equity, mode shift, make money
  * Collection:
    * off vehicle: reduces dwell time
    * on vehicle
      * pay enter
      * pay leave
  * Control
    * driver
    * gate
    * random checks
  * Currency
    * Cash: simple, easy, security risk, time-consuming
    * Prepaid
      * Types: single-ride, day, week, month, stored value, senior, disabled, low-income
      * Device: card, phone
    * Method
      * Self-service e.g. Germany -> random checks
      * Gates
    * Structure
      * flat-fare
      * distance-based
    * Transfers - free or not
    * Off-peak discount
* Improvements
  * Vehicle: more, bigger doors, low floor, electric propulsion
  * Intersections: curb parking, dedicated lanes, turn prohibition
    * Stop location
      * Prioritization: after intersection
      * Green Wave: alternate
      * Bus Sluice: before intersection
  * Stops
    * Types
      * Bay: slow
      * Bulb
      * Curbside
    * Curb-design to catch wheels
    * Types
      * Demand: stop anywhere
      * On-request: push a button or people waiting
      * Stop at all stops
    * Types
      * Local/Express
	* 4-track: headway = time lost by local because of stopping * number of stops for local
	* 2-track: local waits for 2 * minimum headway for express to stop and then go
      * Skip-Stop: A, B, AB
      * Zonal e.g. Munich S-Bahn, Regional Trains, ICE
  * Signal Prioritization
  * Fare Collection
    * Off-vehicle
  * C -> B -> A
  * Routing (fewer left turns)
  * Fewer Stops
  * Timetable Integration
  * Articulated Vehicles
* Scheduling
  1. Trip Building
    1. Compute the necessary headway
    2. Compute the travel time, terminal time, cycle time, and number of vehicles needed
    3. Create the timetable
  2. Block Building
    * Assign Transport Units to depot
  3. Run-cutting
    * Optimize drivers
  4. Rotating Duty Rosters
    * One duty roster for all employees
      * Rotates with a fixed cycle: Lehner
      * Rotates with a weekly cycle: Rüger
    * Main rotation (popular) and side rotation (unpopular)
    * Choice duty roster
    * Individual duty roster