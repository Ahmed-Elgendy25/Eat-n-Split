# Eat-n-Split

## Pay for me or, Pay for you.

The idea of project is you can select a friend and split a bill with this friend by inserting the bill value, and your expense and your friend's expense (bill value - your expense). then you choose who is paying the bill. 
Also you can add friend to select him to pay for his bill or he/she can pay for you.
![image](https://github.com/Ahmed-Elgendy25/Eat-n-Split/assets/108876019/da1416c1-1dda-4869-8d9c-dcd78964cc53)
## Installation
To run the project locally, follow these steps:
1. Clone the repository:
   ```
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```
   cd eat-n-split
   ```
3. Install the dependencies:
   ```
   npm install
   ```
4. Start the development server:
   ```
   npm start
   ```
   This will start the application on your local server (by default, [http://localhost:3000](http://localhost:3000)).
## Usage
Once the application is running, you can interact with the Eat-n-Split project in your web browser. The project provides the following functionalities:
### Pay the Bill for Others
1. On the homepage, you will find a form labeled "Pay the Bill for Others".
2. Enter the total bill amount in the designated input field.
3. Specify the number of participants who will be splitting the bill.
4. Fill out the name and amount paid by each participant in the table provided. You can dynamically add or remove rows as needed.
5. The application will automatically calculate and display the amount owed by each participant.
6. You can choose to pay the bill for others by entering the amount you wish to pay in the designated input field.
7. The application will update the remaining amount owed by each participant accordingly.
### Let Others Pay the Bill for You
1. On the homepage, you will find a form labeled "Let Others Pay the Bill for You".
2. Enter the total bill amount in the designated input field.
3. Specify the number of participants who will be splitting the bill.
4. Fill out the name and amount paid by each participant in the table provided. You can dynamically add or remove rows as needed.
5. The application will automatically calculate and display the amount owed by each participant.
6. You can see the amount owed to you by others in the "Amount Owed to You" section.
7. Share this information with others so they can pay the bill for you.
## Project Structure
The project structure follows the standard conventions of a React.js application. Here is an overview of the main files and directories:
- `src/App.js`: This is the main component that renders the application. It handles the state management and contains the logic for calculating and dividing the bill.
- `src/components/`: This directory contains the reusable components used in the application.
- `src/components/BillForm.js`: This component renders the form for entering the bill details.
- `src/components/ParticipantsTable.js`: This component renders the table for adding participant names and amounts paid.
- `src/components/ParticipantRow.js`: This component renders an individual participant row in the table.
- `src/components/AmountOwed.js`: This component displays the amount owed by each participant.
- `src/App.css`: This file contains the styles for the application.
## Dependencies
The project has the following dependencies:
- React.js: A JavaScript library for building user interfaces.
- React DOM: Responsible for rendering React components in the browser.
- React Scripts: Provides scripts and configuration used by Create React App.
- PropTypes: A library used for defining the types of props passed to components.
These dependencies are managed using npm and will be automatically installed when you run the `npm install` command.
## Contributing
If you would like to contribute to this project, you can fork the repository, make your changes, and submit a pull request. Your contributions are greatly appreciated!
## License
This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as per the terms of the license.
## Acknowledgements
This project was created as a practical demonstration of React.js capabilities. It was built with the help of various online tutorials and resources. Special thanks to the React.js community for their excellent documentation and support.
