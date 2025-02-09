# Vehicle-Builder

An application that prompts the user to either create a new vehicle or select an existing vehicle. After going through the creation or selection process, the user is able to perform certain actions with the selected vehicle. The user is returned to the actions menu after each action until they decide to exit the application.

## Features

- Create new vehicles (Truck, Motorbike, Car)
- Select existing vehicles
- Perform actions with the selected vehicle (e.g., tow, wheelie)
- View detailed information about the vehicle
- User-friendly menu navigation

## Classes and Interfaces

### Classes

- `Vehicle`: The base class for all vehicles.
- `Truck`: Extends `Vehicle` and implements the `AbleToTow` interface.
- `Motorbike`: Extends `Vehicle`.
- `Car`: Extends `Vehicle`.
- `Wheel`: Represents a wheel of a vehicle.

### Interfaces

- `AbleToTow`: Interface for vehicles that can tow other vehicles.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/Vehicle-Builder.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Vehicle-Builder
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the application:
    ```sh
    npm start
    ```
2. Follow the prompts to create or select a vehicle.
3. Perform actions with the selected vehicle.
4. View detailed information about the vehicle.
5. Exit the application when done.