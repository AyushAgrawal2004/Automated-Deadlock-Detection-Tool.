# Deadlock Detection Simulator

## Overview
This project is a **Deadlock Detection Simulator** built using **HTML, JavaScript, and Bootstrap**. It allows users to input the number of processes and resources, allocate resources, and detect potential deadlocks in a system using the **Banker's Algorithm**.

## Features
### Initial Features
- **User Input for Processes and Resources**: Allows users to specify the number of processes and resource types.
- **Dynamic Allocation Matrix**: Users can enter allocation values dynamically.
- **Deadlock Detection Algorithm**: Implements an algorithm to detect deadlocks based on available resources and process allocation.
- **Bootstrap UI**: A clean and responsive user interface.
- **Output Display**: Shows results indicating whether a deadlock is present.

### New Features and Enhancements
1. **Enhanced Input Validation**: Inline validation ensures users enter positive numbers.
2. **Reset Button**: Clears all inputs and results with a single click.
3. **Process-Resource Matrix Display**: Visual representation of allocated resources.
4. **Detailed Console Logging**: Logs detailed steps of the deadlock detection process for debugging.
5. **Modal Popup for Deadlock Suggestions**: Displays resolution suggestions in a Bootstrap modal.
6. **Save and Load Configuration (Local Storage)**: Saves user inputs and reloads them upon revisiting the page.
7. **Light/Dark Mode Toggle**: Allows switching between light and dark themes for better accessibility.

## Setup & Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/deadlock-simulator.git
   ```
2. Navigate to the project folder:
   ```sh
   cd deadlock-simulator
   ```
3. Open `index.html` in your browser.

## Usage Instructions
1. Enter the **number of processes** and **resource types**.
2. Click **Setup** to generate the allocation input fields.
3. Enter the allocation values and click **Start Detection**.
4. The system will indicate if there is a deadlock and provide a safe sequence if applicable.
5. Use the **Reset** button to clear all inputs.
6. Check the **console logs** for step-by-step details.
7. Use the **theme toggle** for light/dark mode.

## Contributions
Feel free to contribute by submitting **pull requests**, reporting **issues**, or suggesting new **features**!

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

Made with ❤️ by [AYUSH AGRAWAL]

