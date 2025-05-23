# Fulfillment Information Service
This project models a simple fulfillment information system that can be used by warehouse fulfillment teams to retrieve organized information about product stock information.

No more manually sifting through raw order data!📜

### Here's where you'll find the functionality

* List of all items to pick for the day (workflow #1) at ``` /pickingpage ```
* List of order information for packing (workflow #2) at ``` /packingpage ```

On each of these pages, the warehouse team simply needs to select a date and click Submit. So, the team can seek picking/packing information from anytime in the past.

### How to set it up
1. Clone the project to your local environment
2. Ideally use Node.js (22.14.0)
3. Run ```yarn install``` in ```/``` to install dependencies
4. As the project uses the Yarn package manager, run ```yarn start``` here in the project ```/``` root directory to simultaneously start the front and backends.

### Notes on project structure
* The Express-based backend is located in ```/backend```
  - Project data is located in ```/backend/src/data/``` as ```.json``` files
* The React/Next.js frontend is located in ```/frontend```
Both the frontend and backend can also be started separately. Please refer to their READMEs for details.

### Notes on Testing and Data
* the 'database' of ```.json``` files is located in ```/backend/src/data/```
  - Use these dates in the UI to get data: **2024-03-30**, **2024-03-31**, **2024-04-01**, **2024-04-02**, **2025-02-02** and **2025-01-05**
* Backend unit tests are located in ```/backend/tests```
* Frontend unit tests are located in a ```__tests__``` directory in each of ```/frontend/src/pages```, ```/frontend/src/components``` and ```frontend/src/lib```
* **The most recent code coverage report had 100% coverage, as requested in the assignment**

