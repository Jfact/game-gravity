# Cube Simulation with Gravity and Thrust

This project simulates the movement of a cube under the influence of gravity and thrust on different celestial bodies. Users can adjust the mass of the cube, the type and amount of fuel, and the gravitational force to observe realistic physics-based movements.

## Features

- **Gravity Selection**: Choose from various celestial bodies to apply their respective gravitational forces.
- **Thrust Control**: Apply thrust using different fuel types, affecting the cube's acceleration.
- **Mass Adjustment**: Set the mass of the cube and the fuel separately.
- **Realistic Physics**: The simulation considers gravity, thrust, and mass to calculate the cube's movement and distance traveled.
- **Distance Tracking**: Displays the total distance traveled by the cube in kilometers.

## How to Use

1. **Select Gravity**: Use the dropdown menu to select the celestial body whose gravity you want to simulate.
2. **Select Fuel Type**: Use the dropdown menu to select the type of fuel, which affects the thrust multiplier.
3. **Set Cube Mass**: Enter the mass of the cube in kilograms in the provided input field.
4. **Set Fuel Mass**: Enter the mass of the fuel in kilograms in the provided input field.
5. **Control the Cube**: Use the arrow keys to move the cube:
   - **Up Arrow**: Apply thrust to move the cube upward (if there is fuel).
   - **Down Arrow**: Move the cube downward.
   - **Left Arrow**: Move the cube left.
   - **Right Arrow**: Move the cube right.

## Physics Calculations

- **Gravity Force**: \( F_{\text{gravity}} = \text{gravity} \times \text{total mass} \)
- **Thrust Force**: \( F_{\text{thrust}} = \text{base thrust} \times \text{fuel multiplier} \)
- **Total Mass**: \( \text{total mass} = \text{mass of cube} + \text{mass of fuel} \)
- **Acceleration**: \( a = \frac{F_{\text{thrust}}}{\text{total mass}} \)
- **Distance Traveled**: Updated based on vertical movement and converted to kilometers.

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd cube-simulation
    ```
3. Open `index.html` in your web browser to start the simulation.

## File Structure

- `index.html`: The main HTML file containing the structure of the webpage.
- `style.css`: The CSS file for styling the webpage.
- `script.js`: The JavaScript file containing the logic for the simulation.

## Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License.
